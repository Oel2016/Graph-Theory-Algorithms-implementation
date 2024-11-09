# Graph-Theory-Algorithms-implementation
This repository contains implementations of key graph theory algorithms. These algorithms are essential in solving various optimization and pathfinding problems commonly encountered in computer science and engineering

# Graph Theory Algorithms

This repository contains implementations of key graph theory algorithms. These algorithms are essential in solving various optimization and pathfinding problems commonly encountered in computer science and engineering.

## Algorithms Implemented

1. **Dijkstra's Algorithm**  
   Dijkstra’s algorithm finds the shortest path between nodes in a graph, specifically from a single source node to all other nodes. It works for graphs with non-negative edge weights.

2. **Maximum Flow Algorithm**  
   The Maximum Flow algorithm computes the maximum amount of flow that can move from a source to a sink in a flow network. This implementation uses the Ford-Fulkerson method with the Edmonds-Karp algorithm as an underlying strategy, leveraging BFS to find augmenting paths.

3. **Traveling Salesman Problem (TSP)**  
   The Traveling Salesman Problem is a combinatorial optimization problem. Given a set of cities and distances between them, the TSP seeks the shortest possible route that visits each city once and returns to the origin city. This repository provides both exact and heuristic approaches to solving TSP.

## Requirements

- Python 3.x
- NetworkX (for graph creation and manipulation)
- Matplotlib (for optional graph visualization)

To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
