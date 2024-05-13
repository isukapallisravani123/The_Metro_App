# The_Metro_App

-> The code utilizes a **graph data structure** implemented using defaultdict from collections module, representing a transportation network with stations as vertices and connections as edges.
 
-> **Heapq module** is employed to create priority queues for efficiently implementing Dijkstra's algorithm to find the shortest path based on either distance or time.

-> **Dijkstra's algorithm** is implemented twice in the code: one for finding the shortest path based on distance and another for time.
  
-> **Defaultdict** is used to initialize the graph with an empty list for each vertex, ensuring efficient storage and retrieval of station connections.
  
-> The code employs **set data structure** to track directed edges, enabling the handling of one-way connections within the transportation network.

-> **Directed_edges** set keeps track of one-way connections, ensuring proper handling of directed edges in the graph.

-> The **user interface** allows users to input source and destination stations, choose between finding the shortest path based on distance or time, display available stations, and exit the program.
