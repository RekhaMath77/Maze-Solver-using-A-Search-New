🧩 Maze Solver using A* Search Algorithm

This project implements a Maze Solver using the A* (A-Star) Search Algorithm to find the shortest path from a start point to a goal while avoiding obstacles.
It demonstrates how heuristic-based search improves efficiency over uninformed search algorithms.

📌 Project Overview

The maze is represented as a 2D grid

Each cell is treated as a node

The algorithm finds the optimal (shortest) path

Handles cases where no valid path exists

Includes a simple console visualization

🧠 Algorithm Used
A* Search Algorithm

A* uses the function:

f(n) = g(n) + h(n)


Where:

g(n) → Cost from start to the current node

h(n) → Heuristic (Manhattan Distance)

f(n) → Estimated total cost

Heuristic Function

Manhattan Distance

h = |x1 - x2| + |y1 - y2|

🛠️ Tech Stack

Language: Python

Concepts:

Artificial Intelligence

Graph Search

Heuristics

Pathfinding Algorithms

📂 Maze Representation

0 → Free cell

1 → Wall / Obstacle

Example:

maze = [
    [0, 0, 0, 0, 1],
    [1, 1, 0, 1, 0],
    [0, 0, 0, 0, 0],
    [0, 1, 1, 1, 0],
    [0, 0, 0, 0, 0]
]

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/maze-solver-a-star.git


Navigate to the project folder:

cd maze-solver-a-star


Run the program:

python maze_solver.py

📊 Sample Output

Shortest Path Found:

[(0,0), (0,1), (0,2), (1,2), (2,2), (2,3), (2,4), (3,4), (4,4)]

Console Visualization

* → Path

# → Wall

. → Free cell
