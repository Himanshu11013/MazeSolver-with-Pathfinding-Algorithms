# MazeSolver with Pathfinding Algorithms

MazeSolver with Pathfinding Algorithms is a C++ application that provides an interactive visualization and solving of mazes using advanced pathfinding algorithms. It includes implementations of Dijkstra's algorithm, Breadth-First Search (BFS), Depth-First Search (DFS), and A* (A-star) to find the shortest paths from a starting point to a designated endpoint within a grid-based maze.

## Features

- **Graphical Visualization**: Utilizes SFML for interactive maze creation and pathfinding visualization.
- **Multiple Algorithms**: Supports Dijkstra's, BFS, DFS, and A* algorithms for pathfinding.
- **Interactive Maze Editing**: Users can create mazes, set start and end points, and add/remove walls interactively.
- **Path Highlighting**: Highlights the shortest path found by the chosen algorithm.
- **Performance Metrics**: Displays the algorithm's runtime and pathfinding efficiency.
- **User-Friendly Interface**: Commands are entered via keyboard input, providing intuitive control over maze generation and solving.

## Prerequisites

Before running MazeSolver, ensure you have the following installed:

- **SFML Library**: MazeSolver utilizes SFML for its graphical interface. Make sure SFML is installed on your system. You can install SFML using your system's package manager or by downloading it from [SFML website](https://www.sfml-dev.org/).

- **C++ Compiler**: MazeSolver is written in C++ and requires a C++ compiler that supports C++11 standard or higher.

## Getting Started

To run the MazeSolver application, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/MazeSolver.git
   cd MazeSolverCompile the Application:
2. Compile the main.cpp file using your preferred C++ compiler with SFML linked. Adjust the compilation command based on your system setup.

3. Run the Application:
Execute the compiled binary to launch the MazeSolver application.
### Usage
Upon launching the application, you will be prompted to choose one of the following algorithms:

1: Dijkstra - Finds the shortest path using uniform edge weights.
2: BFS (Breadth-First Search) - Explores all neighbors at the present depth level before moving on to nodes at the next depth level.
3: DFS (Depth-First Search) - Explores as far as possible along each branch before backtracking.
4: A (A-star)* - Uses a heuristic to estimate the cost of the shortest path from a node to the target node.
### Algorithms
Dijkstra's Algorithm
Dijkstra's algorithm finds the shortest paths from a source node to all other nodes in a graph with non-negative edge weights. It uses a priority queue to always expand the shortest known path.

Breadth-First Search (BFS)
BFS explores nodes in layers, exploring all neighbors at the present depth level before moving on to nodes at the next depth level. It guarantees the shortest path in an unweighted graph.

Depth-First Search (DFS)
DFS explores as far as possible along each branch before backtracking. It does not guarantee the shortest path but is useful for exploring all paths in a graph.

A* Algorithm
A* is a heuristic search algorithm that uses a combination of the actual cost to reach a node (g) and the estimated cost to the target (h) to determine the order of exploration. It ensures the shortest path in a weighted graph.

Visualization
The MazeSolver application provides a visual representation of the maze creation, editing, and pathfinding process. Walls, start, and end points are graphically represented using SFML graphics, allowing for an intuitive understanding of how algorithms navigate through the maze.

## screenshots
![Initial Maze Setup](initial.png)
*Initial Maze Setup*

![Final Path Highlighted](Final.png)
*Final Path Highlighted*
