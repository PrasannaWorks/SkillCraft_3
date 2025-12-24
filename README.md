# SkillCraft_3
# Task-3: Sudoku Puzzle Solver Using Java

# Problem Explanation:

Sudoku is a logic-based number puzzle played on a 9×9 grid, where:

1. Each row must contain numbers 1 to 9 without repetition
2. Each column must contain numbers 1 to 9 without repetition
3. Each 3×3 sub-grid must also contain numbers 1 to 9 without repetition

* In this task, the program is given an unsolved Sudoku grid, where:
* 0 represents an empty cell
* Pre-filled numbers must not be altered

The objective is to automatically fill in the missing numbers while maintaining all Sudoku rules.

# Approach Used: Backtracking Algorithm

Why Backtracking?

Sudoku is a constraint satisfaction problem, and backtracking is one of the most effective techniques to solve it.

How Backtracking Works:
* Find an empty cell (0)
* Try placing numbers from 1 to 9
* Check if the number is valid:
* Not present in the same row
* Not present in the same column
* Not present in the same 3×3 box
* If valid, place the number and move to the next empty cell
* If no number fits, backtrack and try a different value

This continues until the entire grid is filled correctly.

# Program Execution Flow:

* Input Sudoku grid is defined (0 = empty cell)
* Program searches for empty cells
* Backtracking algorithm tries valid numbers
* Invalid paths are discarded automatically
* Completed Sudoku grid is printed

# Key Concepts Demonstrated

* Backtracking algorithm
* Recursion
* 2D arrays
* Constraint validation
* Problem decomposition
* Logical problem solving
