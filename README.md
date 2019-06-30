# Graph-DataStructure
## structure
there is list of list about adjacency list that indicate each node what is the other nodes connecte to it : thtere is a list that contain the number of the node or the index and each node in the list contain another list that contains (pointing to) another list that contain the destnation and the weight we used a class for this to make it easy for the other functions.

## degree centrality
it has two classes:
1. Edge class: that gets the destination and the weight 
2.Graph class: that contains graph (you gaive the num of nodes that will be connented to a certain node) and add_edge (you give it the src(index node),destination, weight ) overall these two mke the structure (edges it's name).
we will return edges[node].Count.

## clossness centrality
it has 3 functions:
1. Connect: if it is directly connected or not
2. dijkstra: to find the shortest path between needed node and other node. it picks te unvisited vertex with the lowest distance(weight), calculate the distance through it to each unvisited neighbour and updates the neighbour's distance if it is smaller , mark visited when done with neighbour's, at the beginning all carry infinity and the source or the beginning node carrys zero.
3.shortest distance:gets the shortest distance for the node with some comparsios and returns the index node.

## viualization
draw nodes with random axis and draw the link between connected nodes by lines from the center of each node to center of nodes that connects to it. 

### input in GUI
1. number of edges.
2. number of nodes.
3. click visualiztion button.
4.minimize or close form.
choose the name of the function and id of the node.
NOTE:
* to enter different graphs uou should close the exe and re-open it.
* you should click visualization before choosing the function

