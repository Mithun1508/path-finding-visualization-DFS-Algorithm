

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

Dijkstra's Algorithm (weighted): It guarantees the shortest path Dijkstra's algorithm optimizes for the shortest cost path to get from the start vertex to a given vertex. 
We ensure every iteration we are improving our tentative costs from a fully optimized vertex.

Breath-first Search (unweighted): a great algorithm; guarantees the shortest path

Depth-first Search (unweighted): Not Good Algorithm for pathfinding; does not guarantee the shortest path

# SET-UP
1) Every square is a node.

2) Every node is connected to the four nodes on its north, east, south, west direction.

3) Initial number on the node is randomly generated and represents the difficulty in reaching that node from its surrounding nodes.
Final number updated on the node is the cost of reaching that node from the starting point. Initial cost to every node except the first, is infinity.

# STEPS:
   1) Every square is a node.

   2)Every node is connected to the four nodes on its north, east, south, west direction.

   3)Initial number on the node is randomly generated and represents the difficulty in reaching that node from its surrounding nodes.
Final number updated on the node is the cost of reaching that node from the starting point. Initial cost to every node except the first, is infinity.

# DEMO:
You can access it here (use Google Chrome!): 
http://localhost:63342/path-finding-visualization/index.html?_ijt=emthdjjon5m89kkcjo0d5tadus&_ij_reload=RELOAD_ON_SAVE



