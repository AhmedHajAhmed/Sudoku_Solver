# Sudoku_Solver

In this project, I write a Sudoku solver algorithm using backtracking. 

The algorithm will follow the following steps: 
1. Find empty space
2. Try to place the digits 1-9 in the empty space
3. Check if that digit is valid in the current spot based on the current board

a. If the digit is valid, recursively attempt to fill the board using steps 1-3.

b. If it is not valid, reset the square the algorithm just filled and go back to the previous step.

5. Once the board is full, we have found the solution.
