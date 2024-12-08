# Flight Route Visualization

This project is a **Flight Route Visualization System** that allows users to find and visualize the top flight routes between two airports based on various constraints like the shortest distance and limited stops. It leverages **Dijkstra's algorithm** for pathfinding and provides an interactive map interface for route visualization.

---

## Features

- **Interactive Map Visualization**: Displays flight paths on a 2D map.
- **Shortest Path Calculation**: Uses Dijkstra's algorithm to calculate the shortest paths between airports.
- **Top-K Pathfinding**: Retrieves multiple optimal routes based on user-defined constraints (e.g., maximum stops).
- **Custom Animations**: Animates the flight path on the map.
- **Airport Dataset**: Includes a preloaded JSON file with airport locations and distance matrix.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/flight-route-visualization.git
   ```

## Technical Details

- **Algorithm**: Dijkstra's algorithm is used to find the shortest paths between airports.
- **Visualization**: Animates paths between waypoints on a 2D plane.
- **Data Handling**: Airport locations and distances are stored in a JSON file and loaded dynamically.
- **Priority Queue**: Implements a custom MinPriorityQueue for efficient pathfinding.

---

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **JSON**

---
