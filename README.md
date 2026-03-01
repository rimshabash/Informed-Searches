# Informed-Searches
# AI Grid-Based Pathfinding Visualizer

An interactive GUI-based Pathfinding Visualizer built using Python and Pygame.
This project demonstrates and compares multiple search algorithms including uninformed and informed strategies on a dynamic grid.
## Features

Interactive Grid (Resizable: 10×10 to 30×30)

Supports 4-directional + Diagonal Movement

Dynamic Start / Goal Selection

Multiple Goal Re-selection Support

Real-Time Visualization:

🟦 Expanded Nodes

🟨 Visited Nodes

🟩 Path

Adjustable Cell & Font Size (Auto-Scaling)

Goal Status Indicator (In Process / Found / Not Reachable)

Expansion Order Visualization

Cost Display (g(n), h(n), f(n) where applicable)

## Implemented Algorithms
### Uninformed Search

Breadth First Search (BFS)

Depth First Search (DFS)

Uniform Cost Search (UCS)

Iterative Deepening DFS (IDDFS)

### Informed Search

Greedy Best-First Search

Manhattan Heuristic

Euclidean Heuristic

A* Search

Manhattan Heuristic

Euclidean Heuristic

## Heuristics Used
### Manhattan Distance
h(n) = |x1 - x2| + |y1 - y2|

Best suited for 4-directional movement.

### Euclidean Distance
h(n) = √((x1 - x2)^2 + (y1 - y2)^2)

More accurate when diagonal movement is allowed.
## Installation
### Clone the Repository
git clone https://github.com/Rimsha/Informed-Searches.git
cd your-repository-name

### Install Dependencies
pip install pygame

Make sure Python 3.8+ is installed on your system.
### How to Run
python main.py

## Visualization Colors
Color	Meaning
🟨 Dark Yellow	(Visited)
🟦 Blue	(Expanded Nodes)
🟩 Green	(Path)
⚫ Black (Wall) 
🔴 Dark Red	(Goal Node)
🟢 Dark Green	(Start Node)


## Experimental Analysis

Each algorithm was tested under:

### Best Case Scenario

Goal located near start

Minimal obstacles

Minimal node expansion

### Worst Case Scenario

Goal far from start

Heavy obstacles

Large portion of grid explored

Screenshots of both cases are included in the project report.

## Learning Outcomes

Understanding uninformed vs informed search

Comparing optimality and completeness

Studying heuristic impact

Observing expansion behavior

Analyzing cost vs performance trade-offs

## Dependencies

Python 3.8+

## Development Process

The repository includes multiple commits reflecting iterative development:

Grid creation

BFS/DFS implementation

UCS cost correction

Heuristic integration

Diagonal movement support

Visualization improvements

Goal status fix

Cost calculation correction

GUI scaling enhancement

## Author

Rimsha
AI Search Algorithms Project
