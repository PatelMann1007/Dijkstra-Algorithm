# Dijkstra-Algorithm

# Graph Shortest Path Visualizer

This project demonstrates how to load a graph from a text file, calculate the shortest path between two places using Dijkstra's algorithm, and visualize the graph along with the shortest path using Matplotlib and NetworkX.

## Features

- **Graph Loading:**  
  Loads an undirected weighted graph from a text file (`places.txt`).

- **Shortest Path Calculation:**  
  Uses Dijkstra's algorithm to find the shortest path between a specified starting point and destination.

- **Graph Visualization:**  
  Visualizes the graph with nodes and edges using NetworkX. The shortest path is highlighted in red.

## File Structure
 ├── places.txt # Contains graph data in the format: Place1,Place2,Distance 
 ├── main.py # Main Python script containing graph loading, Dijkstra's algorithm, and visualization code └── README.md # This file
 
## Dependencies

- Python 3.x
- Matplotlib
- NetworkX

You can install the required packages using pip:

pip install matplotlib networkx

## Run Code

python main.py
