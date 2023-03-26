# Vim-Commands-

i -> insert mode
Esc -> command mode

## command mode commands:-(go using Esc button)

h -> go left
j -> go down
k -> go up
l -> go right
G -> go down below
gg -> go full up

dd -> delete a line
d -> delete entireblock of code -> after deleting it also copies what has been deleted to clipboard

u -> undo 
ctrl+r -> redo

yy -> copies line to clipboard
p -> paste below (it will go below)
P -> paste above


{ -> go up a block of code
} -> go down a block of code
number+ (h, j, k, l)+({, })+ (dd)
ex:- 20j goes 20 lines down
     10} goes 10 curly braces down
     
o(small) -> insert a line "below" and goes to insert mode
O(caps) -> insert a line "above" and goes to insert mode
     
## Visual mode:-(go using 'V'(capital))

to select group and visually see what you have selected
then use commands like d, ctrl+r, etc ..

## moving Horizontally:- 
w -> takes to next word so skips a word at a time
b -> takes one word back
:30 -> takes to line 30
0 -> zero take to very beginning
$ -> go to end of the line
W -> ignores punctuation
B -> goes back but ignores punctuation
t -> stand for go to example(t! goes to one to the left of ! in the line)
% -> it is helpful for navigating end of cursors and etc ..(example %d deletes selected %column)
