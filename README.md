# Sudoku
This notebook contains a Sudoku solver in python.
There is a basic algorithm which solves sudoku by recursively updating cells by checking which values are already in their rows, columns and squares.
This algorithm is efficient but there are tractable grids which it won't solve.

The 2nd algorithm proceeds by brute force, guessing the value for cells where it doesn't have enough information, then proceeding until it finds a contradiction or a solution. 
When it find a contradiction it backtracks and tries another solution.
This algorithm is inefficent but guaranteed to find a solution if it exists.

I also include a csv files containing lots of (easy) unsolved grids and a csv file from which you can upload harder problems.
