Question 1

Consider the Depth First Search graph algorithm versus the Breadth First Search algorithm. 
They are very similar, except one uses a stack and the other uses a queue. How does the choice of datastructure 
in the affect the execution of the respective algorithms?

answer 1:
In Breadth First Search algorithm, one vertex is selected at a time when it is visited and marked
then its adjacent are visited and stored in the queue, which makes it slower than the Depth First Search graph algorithm.
Also, it makes Breadth First Search algorithm is more suitable for searching solutions which are closer to the given one.

Question 2

What is the difference between a tree and a graph?

A tree does not have a cycle, but a graph does. A graph contains nodes and edges, but a tree only has nodes.

Question 3

In the circular queue datastructure we have front and back variables. 
What is their purpose? Why do we design the queue this way?

Front points to the beginning of the queue and Rear points to the end of the queue. Since queue has the feature "First in First out", we need front and back to
keep track of the front and back variable to push or pull.

Question 4

Encode the following graph as an adjacency matrix

see the image for question 4

Question 5

For the graph in the previous question, write out the steps of Dijkstra's Algorithm 
to find the shortest path between Node 1 and Node 11. For each step, write down 
the Unvisited set U, the Visited set V, and the current tenative distance vector D.
