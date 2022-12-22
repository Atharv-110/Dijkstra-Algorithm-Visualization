
# DIJKSTRA ALGORITHM VISUALIZATION

Dijkstra algorithm is a single-source shortest path algorithm. Here, single-source means that only one source is given, and we have to find the shortest path from the source to all the nodes.

Dijkstra's algorithm allows us to find the shortest path between any two vertices of a graph.

It differs from the minimum spanning tree because the shortest distance between two vertices might not include all the vertices of the graph.

## TECH STACK
- Python & it's Libraries
    - pygame
    - Tkinter
    - sys
## WORKING OF PROJECT

- The Dijkstra algorithm begins at a node and checks each of its neighbours as it adds those neighbours to the queue. You can create black barriers by using the left click. These halt the algorithm queue and allow the queued nodes to circumvent the barriers.

<div align="center">
<img width="35%" src="https://raw.githubusercontent.com/Atharv-110/Dijkstra-Algorithm-Visualization/main/Assets/output1.png"/>
</div>

- The end node, which is yellow, is created with a right click. Any key press launches the programme.

<div align="center">
<img width="35%" src="https://raw.githubusercontent.com/Atharv-110/Dijkstra-Algorithm-Visualization/main/Assets/output2.png"/>
</div>

- In the first picture, the programme is about halfway through, and in the second, it is finished. The visited notes are represented by green nodes, while the queued notes are represented by red nodes. The programme ends after visiting the target node, and the shortest path is displayed in blue.

<div align="center">
<img width="35%" src="https://raw.githubusercontent.com/Atharv-110/Dijkstra-Algorithm-Visualization/main/Assets/output3.png"/>&nbsp;&nbsp;&nbsp;&nbsp;
<img width="35%" src="https://raw.githubusercontent.com/Atharv-110/Dijkstra-Algorithm-Visualization/main/Assets/output4.png"/>
</div>

- Below is a target node which has been surrounded with barrier nodes the program goes through all nodes in the array and once it has completed without finding the target node a message with no solutions found pops up.

<div align="center">
<img width="35%" src="https://raw.githubusercontent.com/Atharv-110/Dijkstra-Algorithm-Visualization/main/Assets/output5.png"/>
</div>

## ACKNOWLEDGEMENTS

 - [Dijkstra Algorithm (Theory)](https://www.programiz.com/dsa/dijkstra-algorithm)
 - [pygame Docs](https://www.pygame.org/docs/)
 - [tkinter Docs](https://docs.python.org/3/library/tkinter.html)
 
