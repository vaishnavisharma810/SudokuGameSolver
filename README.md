# SudokuGameSolver
Given a partially filled 9×9 2D array ‘grid[9][9]’, the goal is to assign digits (from 1 to 9) to the empty cells so that every row, column, and sub grid of size 3×3 contains exactly one instance of the digits from 1 to 9. 


Suppose we have a Sudoku grid and we have to solve this famous number maze problem, Sudoku. We know that Sudoku is a 9 x 9 number grid, and the whole grid are also divided into 3 x 3 boxes There are some rules to solve the Sudoku.
•	We have to use digits 1 to 9 for solving this problem.
•	One digit cannot be repeated in one row, one column or in one 3 x 3 box.
Using backtracking algorithm, we will try to solve Sudoku problem. When some cell is filled with a digit, it checks whether it is valid or not. When it is not valid, it checks for other numbers. If all numbers are checked from 1-9, and no valid digit found to place, it backtracks to previous option.
