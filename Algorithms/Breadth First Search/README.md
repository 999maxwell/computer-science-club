# Breadth-First Search
Let's say we wanted to find out the minimum number of steps the knight could take to get to the pawn.

<img src="chess.png" width="300">

We could probably determine the answer to this problem fairly quickly in our head. But how would we use a computer to solve this problem efficiently?

Breadth-first search, or simply BFS, is a search algorithm which can be used to find the minimum number of steps to get from one place to another. BFS uses a data type called a "queue", which follows a First-In-First-Out (FIFO) method. This means that the first object added into a queue will always be the first to be removed.

<img src="queue.png" height="250">

To start BFS, a tree node (the starting point of BFS) is added to a queue.

<img src="tree1.png" height="200">

Its neighbors, or surrounding nodes, are then scanned and added to the queue as well.

<img src="tree2.png" height="200">

After doing so, the tree node is then removed from the queue, and the next node in the queue is scanned for neighbors as well. This process continues until all nodes have been checked.

<img src="tree3.png" height="200"> <img src="tree4.png" height="200"> <img src="tree5.png" height="200"> <img src="tree6.png" height="200">
<!-- 46ff00ff (green) 6a6a6aff (grey) fcff00ff (yellow)-->