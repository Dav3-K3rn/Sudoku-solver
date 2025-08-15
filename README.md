# Sudoku-solver
# Overview

This program provides a complete Sudoku solver that can solve any valid 9x9 Sudoku puzzle. It uses a backtracking algorithm to systematically try different numbers and backtrack when a solution path doesn't work.

# Features

Automatic Puzzle Solving: Solves any solvable 9x9 Sudoku puzzle
Input Validation: Validates numbers against Sudoku rules (row, column, and 3x3 square constraints)
Visual Display: Shows both the original puzzle and the solved solution
Error Handling: Detects and reports unsolvable puzzles

# How It Works

The solver uses the backtracking algorithm:

Find Empty Cell: Locates the first empty cell (represented by 0)
Try Numbers: Attempts numbers 1-9 in the empty cell
Validate: Checks if the number is valid according to Sudoku rules:

Not already present in the same row
Not already present in the same column
Not already present in the same 3x3 square


Recurse: If valid, moves to the next empty cell
Backtrack: If no valid number works, backtracks and tries a different number
