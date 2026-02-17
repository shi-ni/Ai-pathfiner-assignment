# AI Pathfinder - Uninformed Search Algorithms

This project implements six fundamental uninformed search algorithms to visualize pathfinding in a grid environment with dynamic obstacles.

## Algorithms Implemented

1. **Breadth-First Search (BFS)**
2. **Depth-First Search (DFS)**
3. **Uniform-Cost Search (UCS)**
4. **Depth-Limited Search (DLS)**
5. **Iterative Deepening DFS (IDDFS)**
6. **Bidirectional Search**

## Features

- Step-by-step visualization of search algorithms
- Dynamic obstacle generation during runtime
- Interactive GUI with real-time updates
- Support for 8-directional movement (including diagonals)
- Path re-planning when obstacles block the current path

## Requirements

- Python 3.7+
- tkinter (usually comes pre-installed with Python)

## Installation

No additional packages required if you have Python installed with tkinter.

```bash
# Clone the repository
git clone <your-repository-url>

# Navigate to the project directory
cd ai
```

## How to Run

```bash
python AI_23P_0634_23P_3064.py
```

## Usage

1. Run the program
2. Select a search algorithm from the dropdown menu
3. Click "Start Search" to begin visualization
4. Watch as the algorithm explores the grid and finds the path
5. Click "Reset" to clear and try another algorithm

## GUI Features

- **Blue cell**: Start point (S)
- **Green cell**: Target point (T)
- **Black cells**: Static walls/obstacles
- **Red cells**: Frontier nodes (in queue/stack)
- **Light blue cells**: Explored nodes
- **Yellow cells**: Final path from start to target

## Project Structure

```
ai/
├── AI_23P_0634_23P_3064.py    # Main implementation file
└── README.md                   # This file
```

## Authors

This is a pair assignment for AI 2002 - Artificial Intelligence (Spring 2026)

## License

This project is submitted as part of an academic assignment.
