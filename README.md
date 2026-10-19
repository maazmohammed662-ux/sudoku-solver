# Sudoku Solver

A Java implementation of a 9x9 Sudoku solver using backtracking.

## Approach
Walks the board cell by cell. For each empty cell, tries digits 1-9, checking the row, column, and 3x3 grid for conflicts (isSafe). If a digit leads to a dead end later, it backtracks and tries the next one.

## Run it

javac sudoku.java
java sudoku


## Example output

**Input (unsolved board):**

53..7....
6..195...
.98....6.
8...6...3
4..8.3..1
7...2...6
.6....28.
...419..5
....8..79


**Output (solved board):**

534678912
672195348
198342567
859761423
426853791
713924856
961537284
287419635
345286179
