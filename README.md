# -MAZE.AI-A-Pathfinding-Engine
A sleek, "cyberpunk" styled maze generator and interactive pathfinding visualizer built with vanilla JavaScript and HTML5 Canvas. This project demonstrates the Recursive Backtracker algorithm for maze generation and the A (A-Star)* search algorithm for pathfinding.

# // MAZE.AI //
### A★ Pathfinding Engine

A sleek, "cyberpunk" styled maze generator and interactive pathfinding visualizer built with vanilla JavaScript and HTML5 Canvas. This project demonstrates the **Recursive Backtracker** algorithm for maze generation and the **A* (A-Star)** search algorithm for pathfinding.

## 🕹️ Features
* **Maze Generation**: Uses a recursive backtracker to ensure a "perfect" maze (no loops, every area reachable).
* **AI Pathfinding**: Visualizes the A* search algorithm, showing both the explored nodes and the final optimal path.
* **Customizable Grid**: Adjustable grid sizes ranging from 9x9 to 25x25.
* **Variable Speed**: Control the AI's "thought" process speed from 10ms to 300ms.
* **Dual-Mode Play**: Manually navigate the maze using Arrow keys, WASD, or the on-screen D-pad, or let the AI solve it for you.

## 🛠️ Technical Overview
* **Language**: HTML5, CSS3, JavaScript (ES6+).
* **Rendering**: HTML5 Canvas API for high-performance grid drawing.
* **Tools**: VS.Code, Claude AI.
* **Algorithms**:
* **Generation**: Depth-First Search (DFS) via Recursive Backtracking.
* **Pathfinding**: A* Search using Manhattan Distance as the heuristic.

## 🚀 How to Run
1. Clone this repository or download the `maze_ai_game.html` file.
2. Rename the file to `index.html` (recommended for easy hosting via GitHub Pages).
3. Open the file in any modern web browser.
4. or use the live ver: https://maze-ai.netlify.app/

## 🎨 Legend
* **Cyan Dot**: The Player.
* **Green Square**: The Exit Goal.
* **Purple Shading**: Nodes explored by the AI during search.
* **Gold Line**: The calculated optimal path.
* **Dark Panels**: Walls/Obstacles.

