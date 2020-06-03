### Stacks and Queues
#### What is a Stack
it is type of data structure consist of Nodes every point have a pointer to the next and do not point to previous, the stack we can definde it have Push when we need put node or item into stack, pop to remove item from stack,top from the name it is the top od stack, peek to view the value of top node in stack,isEmpty if the stack empty return true, there is concept in stacks `FILO` first element push in stack and last pop,`LIFO`last element push in stack the first pop.
##### Stack Visualization
stack look like if you can imagin if you have a box the first element push it in the stack it was the top and the last pop but when you push another one it will be the new top, when yiu pop current top and set the next top as top.next.
##### Push O(1)
it always be O(1) operatioon it take the same amount of time,when we push node by assign new top then the next = original.
##### Pop O(1)
to remove item from the top of stack, top node resign to the node that below, you must check isEmpty before pop you can use try/catch block.
##### Peek O(1)
to view the value of top node in stack,you must check isEmpty before Peek you can use try/catch block.
##### IsEmpty O(1)
if the stack empty return true,otherwise return false.
#### What is a Queue
the queue there is some terminology in the queue such as: enqueue it like push in stack it to add item or node to queue,dequeue like the pop in stack to remove item from quenue, front it is mean front or first node in queue, rear the last node in queue, peek view the value of front node,is empty if the queue is empty return true otherwise false, there is concept in stacks `FILO` first element push in queue and last pop,`LIFO`last element push in queue the first pop.
##### Queue Visualization
##### Enqueue O(1)
it done by o(1)operation in time do not matter how many node in queue take same amount of time,the next of rear point on node we are adding , re-assign rear next to the new node,the only way yo access rear node from rear change rear.next to new node.
##### Dequeue O(1)
t done by o(1)operation in time do not matter how many node in queue take same amount of time,first we must check id isEmpty before do dequeue we can do it in try/catch block, create tem it have pointer to front re assign front = next.value, re-assign the next propert on the temp node and return the value of temp.
##### Peek O(1) 
we will check the front Node of queue,after that check if the stack have input yo check if it isEmpty or not after that to make exception, you can use peek .
##### IsEmpty O(1) 
if the stack have input in it will return false otherwise return true.


