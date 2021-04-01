# Game-of-Life
A simulator of John Conway's Game of Life written in python using the pygame library

rules:
each block can be on or off.
if a block is on and it has two or three adjacents which are on, it will stay on.
if a block is off and it has three adjacents which are on, it will turn on.
otherwise, the block will be off.
however when a block is on margins, it has less adjacents than other blocks 
and it means that the rules for them will work different from other blocks.

how to use:
you can turn on an off block by clicking on it and turn off an on block by clicking on it.
by pressing the Return button the program will pause or resume.
by pressing the right button you can update the board for one step.
by pressing the 's' button you can save your work.
by pressing the 'l' button you can load a saved work.
by pressing the 'd' button you can enable 'Drag and Draw'.
