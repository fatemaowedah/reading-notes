### Trees
#### Trees
there is two type Binary Trees and Binary Search Trees, there is a terminology node is:is individual item from data structure, root: the root of first/top, Left Child:positioned to the left of a root or node, Right Child: positioned to the right of a root or node, Edge: link between a parent and child node,Leaf: node that does not contain any children,Height:height of tree by number of edge.
#### Traversals
we can search for a node or print out the content of tree, there is two type of it Depth First: it depend in height of tree there is 3 type of it `Pre-order: root >> left >> right`:root has to be looked at first output its value. When we call preOrder for the first time, the root will be added to the call stack , `In-order: left >> root >> right`, `Post-order: left >> right >> root`, the most common traverse through tree use recrsion, 
#### Binary Trees
tree can have any number of children per node but BT it have two child left and right.
#### Adding a node
when you add a new node to a binary tree is to fill all “child” spots from the top down,we find the first node that does not have 2 child nodes, and insert the new node as a child. We fill the child slots from left to right, 
#### Big O
big o for time if insert new node is O(n), and this specific node is O(n),the worst case is O(n), big o for space complexity, is o(w) w= largest width of tree, the maximum width is 2^(h-1) where h is height of tree, log(n) is number of node.
#### Binary Search Trees
type of tree odes are organized in a manner where all values that are smaller than the root, the location to the left, and the value more than placed in right, it done quickley because we compare the node you are search, if the value is smaller put it in left side, atherwise put it in right side, best way to do it using while loop until hit the leaf or have match.

#### Big O
the most common way to traverse through aa tree is use recursion, the big O of time is O(h) the height of tree, and if we use leaf it reqauire many node for that log(n),and the worst case is o(n), big O but space of Binary Search Tree’s it is o(1) do not use addition space.
