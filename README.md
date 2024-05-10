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

### Usage
#### Running IPython Notebook on Conda

To run an IPython Notebook (`.ipynb` file) on Conda, follow these steps:

1. **Activate Conda Environment:** Open your terminal or command prompt and activate your Conda environment where you have installed Jupyter Notebook:

    `conda activate (enviornment name)`

   Replace `(environment name)` with the name of your Conda environment.

3. **Install Jupyter Notebook (if not installed):** If you haven't installed Jupyter Notebook in your Conda environment, you can install it using the following command:

   `conda install jupyter`
   
5. **Navigate to Notebook Directory:** Use the `cd` command to navigate to the directory where your `.ipynb` file is located.

6. **Launch Jupyter Notebook:** Once you are in the directory containing your notebook file, run the following command to launch Jupyter Notebook:

    `jupyter notebook`
   
8. **Access Notebook in Browser:** After running the above command, Jupyter Notebook will open in your default web browser. You should see a file browser interface where you can navigate to your `.ipynb` file. Click on the file to open and run it.

9. **Run Notebook Cells:** Once the notebook is open, you can run each cell individually by selecting it and pressing `Shift + Enter`. Alternatively, you can run all cells by selecting `Cell` from the menu and choosing `Run All`.

## Happy Solving :)
   
   

