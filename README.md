Sudoku CLI Game (C++)

A fully functional command-line Sudoku game developed in C++. This project demonstrates core programming concepts such as recursion, backtracking, randomization, and user interaction through a console-based interface.

Features
 Random Sudoku puzzle generation
 Backtracking algorithm for solving puzzles
 Multiple difficulty levels:
Easy
Medium
Hard
Expert
Master
 Mistake tracking system
 Option to reveal the solution
 Interactive CLI gameplay
 Learning mode (rules + instructions)
Technologies Used
C++
Standard Libraries:
<iostream>
<algorithm>
<array>
<chrono>
<random>
🧠 How It Works
1. Puzzle Generation
The program first generates a complete Sudoku grid using a backtracking algorithm.
Values are randomized using shuffle() to ensure different puzzles each time.
2. Puzzle Creation
Cells are removed based on selected difficulty level:
Easy → more numbers visible
Hard → fewer numbers visible
3. Gameplay
User inputs:
Row number
Column number
Value
The program checks:
If the move is valid
If it matches the solution
4. Game End
Game ends when:
Player exceeds mistake limit
Player chooses to reveal solution
How to Run
Compile
g++ sudoku.cpp -o sudoku
Run
./sudoku

Recommended: Run in VS Code terminal or any C++ supported compiler.

Gameplay Instructions
Choose an option from the menu:
Play Game
Learn Game
Learn How to Play
Select difficulty level
Enter:
Row number (1–9)
Column number (1–9)
Value (1–9)
Avoid mistakes — limited attempts allowed
Enter Y anytime to reveal the solution
Sudoku Rules
Each row must contain numbers 1–9 without repetition
Each column must contain numbers 1–9 without repetition
Each 3×3 grid must contain numbers 1–9 without repetition
Project Structure
SUDOKU PROJECT/
│── sudoku(run in VS code).cpp
│── CP PROJECT SUDOKU.pdf
│── PROJECT VIDEO.mp4
Limitations
Uses windows.h → may not compile on Linux/Mac without modification
UI is console-based (no GUI)
Basic input validation
Future Improvements
Add graphical interface (GUI)
Add timer & scoring system
Improve input validation
Cross-platform compatibility
Save/load game feature
Author

Khubaib Muhamamd

⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!
