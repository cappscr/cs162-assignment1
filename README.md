# cs162-assignment1
Implement Conway's Game of Life

You will design, implement, and test a program that runs the game of life. Conway’s Game of Life is a standard example of a cellular automaton. This means that you have an array or matrix of cells. Each turn or generation the value of each cell may change based upon its neighbors. To get more background look online, such as: http://en.wikipedia.org/wiki/Conway's_Game_of_Life Please do the research so you understand the terms and how the rules are applied.

The rules are: Each cell has eight neighbor cells. The neighbors are the cells directly above, below, to the right, to the left, diagonally above to the right and left, and diagonally below to the right and left.
1. If an occupied cell has zero or one neighbor, it dies of loneliness.
2. If an occupied cell has more than three neighbors, it dies of overcrowding.
3. If an empty cell has exactly three occupied neighbor cells, there is a birth of a new cell
to replace the empty cell.
4. Births and deaths are instantaneous and occur at the changes of generation.

NOTE- Think this through carefully before you start coding. If you change a cell it can impact those around it. You should determine the changes required for all cells before changing any cell!

There are significant initial questions that you must address in your design. We will limit the visible “world” to 40 x 20 cells. That’s a lot of characters to type in from the keyboard so don’t make the user do it. There are numerous ways to address this problem. That’s why it’s called design! :-) You must give the user the option to start with one of three starting shapes in the grid; a fixed oscillator, a glider, and a glider cannon.

Probably the most difficult part of the design is what you will need to do to handle the cells on the edges. Remember this is a window on an infinite grid. The patterns go on forever. You are just showing them while they are visible in this small window. You may not be able to just stop the patterns at the edge as that may change the behavior. Specifically, any pattern should not change as the object moves out of the visible grid.

You will create your design document BEFORE you start coding. The TA will grade, in part, on how well your implementation matched your design. Remember, in your reflections document you can explain how you had to change the design because your first idea, just didn’t work. Just explain what you learned. Simply stated, program design is identifying the problem to be solved, identify the inputs, specify the desired output, and then develop the algorithm(s) to convert the input into the output. 

You must also describe how you tested your program. In this case you must demonstrate that the rules work for all cells. The edges will be a special case. You have 2 types of horizontal edges and two types of vertical edges. Each corner involves a different combination of these edges. Your reflections must describe how you planned to test these cases and the results of the testing.
