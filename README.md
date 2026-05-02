# Sudoku CLI Game (C++)

A command-line Sudoku game developed in C++. This project demonstrates core programming concepts such as recursion, backtracking, randomization, and user interaction through a console-based interface.

## Features

- Random Sudoku puzzle generation
- Backtracking algorithm for solving puzzles
- Multiple difficulty levels:
  - Easy
  - Medium
  - Hard
  - Expert
  - Master
- Mistake tracking system
- Option to reveal the solution
- Interactive CLI gameplay
- Learning mode with instructions and rules

## Technologies Used

- C++
- Standard Libraries:
  - iostream
  - algorithm
  - array
  - chrono
  - random

## How It Works

### Puzzle Generation
The program generates a complete Sudoku grid using a backtracking algorithm. Values are randomized to ensure different puzzles each time.

### Puzzle Creation
Cells are removed from the completed grid based on the selected difficulty level. Easier levels retain more numbers, while harder levels remove more.

### Gameplay
The user inputs:
- Row number
- Column number
- Value

The program validates the move and checks it against the solution.

### Game End
The game ends when:
- The player exceeds the mistake limit
- The player chooses to reveal the solution

## How to Run

### Compile
```bash
g++ sudoku.cpp -o sudoku
