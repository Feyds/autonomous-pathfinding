# Autonomous Pathfinding Simulation 🚗🧠

An interactive, web-based simulation demonstrating the **A* (A-Star) Pathfinding Algorithm**. This project visualizes how autonomous vehicles and robots calculate the most efficient route from point A to point B while dynamically navigating around user-defined obstacles.

## 🚀 Overview
Pathfinding is the core of autonomous navigation, from industrial robotics to self-driving cars. This simulation uses the A* search algorithm, which intelligently explores paths by calculating a combination of the exact cost from the start (`g-cost`) and the estimated heuristic distance to the target (`h-cost`). 

The application is built entirely with Vanilla JavaScript and CSS Grid, manipulating the Document Object Model (DOM) to render the algorithm's decision-making process in real-time.

## 🛠️ Technologies & Stack
* **Language:** JavaScript (ES6+)
* **Rendering:** HTML5 & CSS Grid
* **Algorithm:** A* (A-Star) with Manhattan Distance Heuristic

## ⚙️ Features
* **Interactive Environment:** Users can draw custom obstacles (walls) on the grid in real-time using mouse events.
* **Live Visualization:** Watch the algorithm scan open nodes (blue) and lock in closed nodes (dark) before plotting the optimal path (gold).
* **Dynamic Grid System:** Mathematical mapping of a 2D coordinate system directly onto browser DOM elements.

## 💻 How to Run Locally / Live Demo
1. No backend or server is required for this project.
2. Clone this repository to your local machine.
3. Open the `index.html` file in any modern web browser.
4. **Click and drag** your mouse across the grid to build walls.
5. Click **"Start Algorithm"** to watch the A* algorithm solve the maze!
