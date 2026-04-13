# 🧠 A* Maze Solver Visualization

This project implements the **A* (A-Star) Search Algorithm** to find the shortest path in a maze/grid.
It also provides a **real-time visualization** of how the algorithm explores nodes and reaches the goal.

---

## 🚀 Features

* 🔍 Implements A* pathfinding algorithm
* 📊 Uses **Manhattan Distance heuristic**
* 🎯 Finds the **shortest path** from start to goal
* 🎥 Real-time visualization using `matplotlib`
* ❌ Handles unreachable cases
* 🧩 Easy-to-modify grid-based maze

---

## 🧠 What is A* Algorithm?

A* is an informed search algorithm that finds the shortest path using:

* **g(n)** → Cost from start node
* **h(n)** → Heuristic (estimated cost to goal)
* **f(n) = g(n) + h(n)** → Total cost

The algorithm always explores the node with the lowest **f(n)** value.

---

## 🖼️ Visualization Legend

| Color     | Meaning       |
| --------- | ------------- |
| 🟦 Blue   | Visited Nodes |
| 🟨 Yellow | Current Node  |
| 🟩 Green  | Start Node    |
| 🟥 Red    | Goal Node     |
| 🟪 Purple | Final Path    |

---

## 📂 Project Structure

```
Syntecxhub_Maze_Solver/
│── a_maze_solver_visualization.py
│── README.md
│── requirements.txt
```

---

## ⚙️ Installation

1. Clone the repository:

```
git clone https://github.com/your-username/Syntecxhub_Maze_Solver.git
cd Syntecxhub_Maze_Solver
```

2. Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ How to Run

```
python main.py
```

---

## 🧪 Example Maze

```python
maze = [
    [0, 0, 0, 1, 0, 0],
    [1, 1, 0, 1, 0, 0],
    [0, 0, 0, 0, 0, 1],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]
```

* `0` → Free path
* `1` → Wall

---

## 📌 Output

* Real-time animation of node exploration
* Final shortest path highlighted
* Console output of path coordinates

---

## 💡 Inspiration

This project was inspired by A* pathfinding visualization concepts and demonstrates how heuristic-based search improves efficiency compared to uninformed search algorithms.

---

## 📈 Future Improvements

* 🔹 Add GUI using Tkinter or PyGame
* 🔹 Compare A* with BFS / Dijkstra
* 🔹 Allow user input for maze
* 🔹 Export animation as GIF

---

## 🙌 Acknowledgment

This project was completed as part of the **Syntecxhub Artificial Intelligence Internship Program**.

---

## 📬 Connect

If you like this project, feel free to ⭐ the repo and connect with me on LinkedIn!

---

