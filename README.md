# sudoku
Finds possible sudoku solutions:
This will need the variable grid to be a 9 by 9 matrix of values based off of an uncompleted sudoku puzzle grid, 
using the figure 0 to represent blank squares. The user of the program will need to go into the code and input the 
matrix with the form "[[0, 0, ...], [0, 0, ...], ...]]. The program will go through submatrices of the size 3 by 3 as
well as the rows and columns to find missing values 1-9. As it works through, if an answer is not found the
program will continue on and return back to said position later. If no solution can be found with the given
information, the program will show that. Otherwise, the code should work for all solvable sudoku problems.
