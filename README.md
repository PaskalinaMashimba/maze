# 🧩 Maze Generator & Solver (C++ & SFML)

This is a graphical maze generation and solving project written in **C++** using the **SFML graphics library**. The program lets users customize maze dimensions, generates a randomized maze using DFS backtracking, and visualizes a path from the start to the exit using BFS (Breadth-First Search).

---

## 🚀 Features

- ✅ Generate customizable mazes with random paths  
- ✅ Visualize the maze using SFML (Simple and Fast Multimedia Library)  
- ✅ Solve the maze using Breadth-First Search  
- ✅ Animates a red circle moving through the path  
- ✅ Fully interactive: User inputs maze size, start point, cell size, and move speed  

---

## 🛠️ Technologies Used

- **C++**
- **SFML (Simple and Fast Multimedia Library)**
- STL (Vectors, Queues, Stacks, etc.)
- DFS & BFS algorithms

---

---

## 🧠 How It Works

### Maze Generation
- Uses **DFS backtracking** to carve out a random path
- Walls and paths are stored in a 2D grid of `enum Cell { WALL, PATH }`

### Maze Solving
- Uses **Breadth-First Search (BFS)** to find the shortest path
- Animates the movement using SFML graphics and a clock delay

---

## 📦 How to Run

### 🧰 Requirements
- C++17 or later
- [SFML 2.5+](https://www.sfml-dev.org/download.php)

### 🔧 Build Instructions

```bash
g++ maze_solver.cpp -o maze_solver -lsfml-graphics -lsfml-window -lsfml-system
./maze_solver
