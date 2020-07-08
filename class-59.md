###  Graphs
####  Graphs
is a non-linear data structure it contain collection of nodes connected by edges(line segments),vertices or node:is a data object that can have zero or more adjacent vertices, Edge:connection between two nodes,Neighbor: its adjacent nodes are connected via an edge, Degree:degree of a vertex is the number of edges connected to that vertex.
####  Directed vs Undirected
each edge is undirected or bi-directiona: that mean that the undirected graph does not move in any direction, Digraph: is a graph where every edge is directed it has direction Each node is directed at another node with a specific requirement, 
####  Complete vs Connected vs Disconnected
depends on how connected the graphs are to other node/vertices there is 3 type: completed: all nodes are connected to all other nodes each vertex is actually connected to every other node on the graph, connected: has all of vertices/nodes have at least one edge  each node is connected to at least one other node or vertices like tree, and disconnected:graph where some vertices may not have edges,some nodes may not always be connected to other nodes or vertices of the graph.
####  Acyclic vs Cyclic
acyclic graph is a directed graph without cycles when a node can be traversed through and potentially end up back at itself we call it as DAG can also be represented as what we know as a tree, Cyclic graph is a graph that has cycles  defined as a path of a positive length that starts and ends at the same vertex.
####  Graph Representation
we can present it by Adjacency Matrix:2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix Row and column represents each vertex of the data structure. The elements of both the column and the row must add up to 1 if there is an edge that connects the two, or zero if there isn’t a connection a sparse graph is when there are very few connections. a dense graph is when there are many connections, Adjacency List:epresent graphs. An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected it easy to view if one vertices connects to another.
####  Weighted Graphs
graph with numbers assigned to its edges. These numbers are called weights, you set the element in the 2D array to represent the actual weight between the two paths. If there is not a connection between the two vertices, you can put a 0, adjacency lists, you must include both the weight and the name of the adjacent vertex.
####  Traversals
Breadth First: starting at a specific vertex/node. This node must be specified when calling the BreadthFirst() method,  graphs can have cycles. When a graph has cycles and we are trying to traverse,need to have some sort of flag that specifies if we have already visited that vertices. Upon each visit, we just set the visited flag from false to true, Enqueue the declared start node into the Queue, Create a loop that will run while the node still has nodes present, Dequeue the first node from the queue,if the Dequeue‘d node has unvisited child nodes, mark the unvisited children as visited and re-insert them back into the queue,Depth First: Push the root node into the stack, Start a while loop while the stack is not empty
Peek at the top node in the stack, If the top node has unvisited children, mark the top node as visited, and then Push any unvisited children back into the stack, If the top node does not have any unvisited children, Pop that node off the stack,repeat until the stack is empty.

####  Real World Uses of Graphs
like:GPS and Mapping, Driving Directions, Social Networks,Airline Traffic,Netflix uses graphs for suggestions of products.
