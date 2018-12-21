# Conways_Game_of_Life
An instance of Conway’s Game of Life consists of an n x n-grid of cells, each of which can be either alive or dead. When the game begins, we specify an initial configuration of living and dead cells. The game then moves through successive generations, in which cells can either die, come to life, or stay the same, according to the following rules:

Before Play this Game, ensure you are in bash environment and can makefile

There is two option in the game, one has a class xwindow file, which could handle the mechanics of getting graphics to display,
another one is print the cell on screen like this
_____
__X__
__X__
__X__
_____

Here is all the command that this game has!

When you run your program, it will listen on stdin for commands. Your program must accept the following commands:
 new n Creates a new n  n grid, where n  1. If there was already an active grid, that grid is destroyed and replaced
with the new one.
 init Enters initialization mode. Subsequently, read pairs of integers x y and set the cell at (x; y) as alive. x represents
the horizontal direction, and y represents the vertical direction. The top-left corner is (0; 0). The coordinates -1 -1
end initialization mode. It is possible to enter initialization mode more than once, and even while the simulation is
running.
 step Runs one tick of the simulation (i.e., transforms the grid into the immediately succeeding generation).
 steps n Runs n steps of the simulation.
 print Prints the grid.
Example!! as follow!!
new 5
init
2 1
2 2
2 3
-1 -1
print
_____
__X__
__X__
__X__
_____
step
print
_____
_____
_XXX_
_____
_____
