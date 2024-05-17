**Delhi Metro Fare Calculator and Route Finder**
Note: This is NOT an ANDROID Application!

**Overview**
This Java program is a simple utility for calculating fare and finding the shortest metro route between two stations on the Delhi Metro network. It provides users with the ability to input the name of the source and destination stations and displays the fare and the shortest route to reach the destination. Additionally, it includes a metro map to aid commuters in navigation.

The project utilizes graph and heap data structures to implement its functionalities. The graph consists of nodes representing metro stations, each containing information such as the station's name, metro corridor, and connecting lines. The edges represent the distance between stations, with the cost of each edge equal to the distance between the connected stations.

Algorithms such as Dijkstra's algorithm, breadth-first search, and depth-first search are employed to determine the shortest path between the source and destination stations. The fare is calculated based on the total distance traveled between the two stations. Finally, the program displays the metro route and total fare to the user.

**DSA Strategies Used**
1. Graph Data Structure: Represent stations and connections between them.
2. Heap (Priority Queue): Implement priority queue for efficient node selection.
3. Dijkstra's Algorithm: Find the shortest path between source and destination stations.
4. Breadth-First Search (BFS): Traverse the graph to find the shortest route.
5. Depth-First Search (DFS): Explore alternative routes in the graph.

**Features**
1. Input source and destination stations to calculate fare and find the shortest route.
2. Display metro route and total fare.
3. Utilize graph and heap data structures for efficient pathfinding.
4. Include a metro map for better navigation.

**Project Structure**
Main.java: Contains the main code for fare calculation, route finding, and user interaction.
Heap.java: Implements the heap data structure for efficient priority queue operations.
