# Sudoku Solver

A Java implementation of a 9x9 Sudoku solver using backtracking.

## Approach
Walks the board cell by cell. For each empty cell, tries digits 1-9,
checking the row, column, and 3x3 grid for conflicts (isSafe). If a
digit leads to a dead end later, it backtracks and tries the next one.

## Run it
javac sudoku.java
java sudoku
