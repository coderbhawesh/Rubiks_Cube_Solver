# Virtual Rubik's Cube Solver

This project models a virtual Rubik’s Cube (3x3) using standard data structures from the STL (Standard Template Library) and implements optimized solving algorithms. The project achieves remarkable solve times for different levels of cube scrambling using various search algorithms.

## Features

- **Three Different Models:** The Rubik’s Cube is represented in three different ways using STL data structures.
- **Efficient Solving Algorithms:** 
  - BFS (Breadth-First Search)
  - DFS (Depth-First Search)
  - IDDFS (Iterative Deepening Depth-First Search)
  - Korf’s IDA* Algorithm (Iterative Deepening A* Search)
- **Optimized Performance:**
  - Solve time under 3 seconds for a cube jumbled 8 times.
  - Solve time under 10 seconds for a cube jumbled 13 times using Korf’s IDA* Algorithm.

## Installation

(UBUNTU)
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rubiks-cube-solver.git
   cd rubiks-cube-solver
   ./bp.sh 
   ./rubiks_cube_solver
