

# Path-finding Visualization With Just HTML, CSS & JavaScript


# PROCESS
CSS & HTML

CSS flexbox (for centering stuff)
CSS grid (to create the 10x10 grid)
JavaScript

querySelector & querySelectorAll (for selecting DOM elements)
setTimeout (to create animation effect)
createElement, getAttribute, setAttribute, appendChild (for modifying the DOM)

# MEET THE ALGORITHMS
This application supports the following algorithms:

# Dijkstra's Algorithm (weighted): It guarantees the shortest path Dijkstra's algorithm optimizes for the shortest cost path to get from the start vertex to a given vertex. 
We ensure every iteration we are improving our tentative costs from a fully optimized vertex.

# Breath-first Search (unweighted): a great algorithm; guarantees the shortest path

# Depth-first Search (unweighted): Not Good Algorithm for pathfinding; does not guarantee the shortest path

# SET-UP
1) Every square is a node.

2) Every node is connected to the four nodes on its north, east, south, west direction.

3) Initial number on the node is randomly generated and represents the difficulty in reaching that node from its surrounding nodes.
Final number updated on the node is the cost of reaching that node from the starting point. Initial cost to every node except the first, is infinity.

# STEPS:
   1. Starting with the chosen node, update the cost of reachable nodes by taking minimum of ( (cost to reach the "coming from" node + difficulty to the visiting node), previously updated cost to the visiting node), set the "coming from" node as parent if the cost is less to come from that node.
   
   2. Repeat the steps for reachable nodes in the sequence of least cost to most cost, until all nodes have been visited.

# DEMO:
You can access it here (use Google Chrome!): 
https://mithun1508.github.io/path-finding-visualization/



