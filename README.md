# Sudoku-Solver
A C++ program that solves a 9x9 Sudoku puzzle using the backtracking algorithm. It fills empty cells while ensuring all Sudoku rules are followed.
## Algorithm Used
This Sudoku solver is implemented using Backtracking Algorithm, a classic technique for solving constraint satisfaction problems.

### How It Work
1.The program searches for an unassigned cell (i.e., a cell with a value of 0).
2.For that cell, it tries all numbers from 1 to 9.
3.It checks if placing that number is valid:
4.The number must not be already present in the same row, column, or 3×3 box.
5.If the number is safe, it assigns the number and recursively tries to solve the rest of the board.
6.If the assignment leads to a dead-end, it backtracks (undoes the assignment) and tries the next number.
7.The process continues until the board is completely filled or no solution exists.

## How to Run
### Prerequisites
A C++ compiler like g++.
A basic terminal or IDE like Visual Studio Code, Code::Blocks, or Dev C++.

### Steps to Compile and Run
1. *Clone the Repository*:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   cd sudoku-solver
