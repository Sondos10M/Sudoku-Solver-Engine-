# 🧩 Sudoku Solver Engine

An efficient **Sudoku Solver** written in **Python** using **Backtracking** and **Recursion** to solve $9\times9$ Sudoku puzzles dynamically.

---

## 📌 Features
- **Backtracking Algorithm**: Solves complex $9\times9$ Sudoku grids efficiently by exploring possible choices and rolling back on invalid states.
- **Constraint Validation**: Checks horizontal rows, vertical columns, and $3\times3$ sub-grids to maintain Sudoku rules.
- **Formatted Terminal Output**: Visualizes the board grid clearly before and after solving.

---

## 🛠️ Tech Stack & Concepts
- **Language**: **Python**
- **Core Concepts**: **Backtracking**, **Recursion**, **Constraint Satisfaction Problems (CSP)**, **State Restoration**

---

## 🚀 How It Works
1. **Find Empty Cell**: Scans the grid for empty slots (represented by `0`).
2. **Validate Placement**: Tests numbers from `1` to `9` to verify row, column, and $3\times3$ sub-grid validity.
3. **Recursion & Backtracking**: Places a valid number and recursively attempts to solve the rest of the board. If a dead-end is reached, it resets the cell to `0` (**Backtracking**) and tries the next number.

---

## 💻 Running the Solver
```bash
python sudoku_solver.py
