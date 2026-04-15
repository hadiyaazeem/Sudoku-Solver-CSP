Sudoku Solver using CSP (AC-3 + Backtracking)
 Overview
This project implements a Sudoku Solver using **Constraint Satisfaction Problem (CSP)** techniques.
It combines:
AC-3 Algorithm (Arc Consistency)
Backtracking Search
MRV Heuristic (Minimum Remaining Values)
The solver efficiently solves Sudoku puzzles of varying difficulty levels.
* Constraint Propagation (AC-3)
* Backtracking Search
* Minimum Remaining Values (MRV)
* Forward Checking
Project Structure
Sudoku-Solver-CSP/
│── sudoku_solver.py
│── easy.txt
│── medium.txt
│── hard.txt
│── veryhard.txt
│── README.md
How to Run
1. Make sure Python is installed
2. Run the script:

```
python sudoku_solver.py
```

---
Features
* Solves multiple Sudoku puzzles
* Supports different difficulty levels
* Tracks:
  * Backtracking calls
  * Failures (dead ends)
* Uses efficient CSP techniques
Difficulty Levels
* Easy
* Medium
* Hard
* Very Hard
Output Example
* Solved Sudoku grid
* Backtracking statistics
## 🛠️ Technologies Used

* Python
* CSP Algorithms (AC-3, Backtracking)

---
Author
Hadia Azeem
