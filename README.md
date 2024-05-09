# Sudoku and Magic Square Solver

## Overview
This Python project implements algorithms to solve two classic puzzle games: Sudoku and Magic Square. The Sudoku solver applies **backtracking** search with heuristics to generate and solve 9x9 Sudoku puzzles, ensuring each row, column, and 3x3 box contains exactly the digits 1 through 9. The Magic Square solver utilizes a **genetic algorithm** to generate and solve 3x3 magic square puzzles, where the sum of each row, column, and diagonal is the same.

## Sudoku Solver
### Problem Description
Sudoku is a numerical puzzle game where the goal is to fill a 9x9 grid with digits from 1 to 9, ensuring no row, column, or 3x3 box contains repeated digits.

### Solution Approach
The Sudoku solver implements **backtracking search** with the following heuristics:
- Minimum Remaining Values (MRV)
- Degree Heuristic
- Least Constraining Value
- Arc Consistency

## Magic Square Solver
### Problem Description
The Magic Square puzzle involves arranging numbers 1 through 9 in a 3x3 grid such that the sum of each row, column, and diagonal is the same.

### Solution Approach
The Magic Square solver utilizes a **genetic algorithm** to find the optimal arrangement of numbers. It employs mutation, crossover, and selection techniques to evolve towards a solution.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Ensure Python 3.x is installed on your system.
4. Run the following commands to execute the solvers:
   - `python main.py`
5. Or you can download the file uplaod it on google drive, and run it on Google Collab.

## Happy Solving :)
   
   

