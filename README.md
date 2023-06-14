
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
<img width="35%" src="https://github.com/Atharv-110/Dijkstra-Algorithm-Visualization/assets/87393095/7b8d002e-c1d5-4056-9fa6-a6e4715b341d"/>
</div>


- The end node, which is yellow, is created with a right click. Any key press launches the programme.

<div align="center">
<img width="35%" src="https://github.com/Atharv-110/Dijkstra-Algorithm-Visualization/assets/87393095/a9cc5cd2-ec72-41c0-8835-d6129c17070b"/>
</div>


- In the first picture, the programme is about halfway through, and in the second, it is finished. The visited notes are represented by green nodes, while the queued notes are represented by red nodes. The programme ends after visiting the target node, and the shortest path is displayed in blue.

<div align="center">
<img width="35%" src="https://github.com/Atharv-110/Dijkstra-Algorithm-Visualization/assets/87393095/f84bbb1f-de6d-4a71-ab82-69240e40d7db"/>&nbsp;&nbsp;&nbsp;&nbsp;<img width="35%" src="https://github.com/Atharv-110/Dijkstra-Algorithm-Visualization/assets/87393095/626b1412-258e-471e-b7ab-75d912d32d2c"/>
</div>

- Below is a target node which has been surrounded with barrier nodes the program goes through all nodes in the array and once it has completed without finding the target node a message with no solutions found pops up.

<div align="center">
<img width="35%" src="https://github.com/Atharv-110/Dijkstra-Algorithm-Visualization/assets/87393095/45bb2c7f-6b6a-4692-b3a3-5573bdf8121b"/>
</div>

## ACKNOWLEDGEMENTS

 - [Dijkstra Algorithm (Theory)](https://www.programiz.com/dsa/dijkstra-algorithm)
 - [pygame Docs](https://www.pygame.org/docs/)
 - [tkinter Docs](https://docs.python.org/3/library/tkinter.html)
 
