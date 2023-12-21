# Labyrinthe Project    

## Introduction
The Labyrinthe project is a Java implementation of a maze-solving algorithm and simulation. It features a prisoner ('D') attempting to escape from a maze ('.') ('#') while avoiding fire ('F'). The maze is represented as a weighted graph, and the prisoner's movement and fire spread are simulated using various algorithms.

## Classes
### WeightedGraph
- **Edge (Arête):** Represents a weighted edge in the graph.
- **Vertex (Sommet):** Represents a vertex in the weighted graph, with individual time, time from the source, heuristic, previous vertex, adjacency list, number, label, and coordinates.
- **Graph (Graphe):** Represents the weighted graph, with a list of vertices and methods to add vertices and edges.

### Labyrinthe
- **AStar(Graph graph, int start, int end, int ncols, int numberV):** Implements the A* algorithm to find the optimal path from the starting point to the destination.
- **Dijkstra(Graph graph, int start, int end, int ncols, int numberV):** Implements the Dijkstra algorithm to find the optimal path from the starting point to the destination.
- ... (Details of other methods)

## Algorithm Choice: AStar and Dijkstra
- **Heuristic (A*):** A* uses a heuristic based on Euclidean distance, providing an efficient approach to guide the search towards the destination.
- ... (Details of other algorithm choices)

## Usage
1. Enter the number of instances and maze dimensions.
2. Enter the layout of the maze for each instance.
3. The program will display results indicating whether the prisoner escapes ('Y') or not ('N').

## Compilation/Execution
- **Compilation:** `javac *.java`
- **Execution:** `java Labyrinthe`
