Learning Outcomes :
1. Acquiring the skills to draw graphs, create vertices, connect them with edges, and handle events using Swing.
2. Implementing various algorithms, such as Breadth-First Search, Depth-First Search, Dijkstra's, and Prim's Algorithms.
3. Designing the application to be extensible, allowing for the integration of additional algorithms in the future.

About - 
This project develops a Java GUI application using Swing framework to create and visualize graphs and graph algorithms, including traversals, spanning trees, and shortest pathfinding.

Users can add or remove vertices and edges by selecting different modes from the Mode menu. Once the graph is created, they can choose one of four algorithms from the Algorithms menu to run on the graph.

The algorithm results for each algorithm is displayed as follows:

-For Breadth-First Search: BFS : <The traversal separated by "->">. Example: BFS : A -> B -> C -> D -> E -> F

-For Depth-First Search: DFS : <The traversal separated by "->">. Example: DFS : B -> C -> A -> D -> F -> E

-For Dijkstra's: A list of = pairs separated by a comma. Example: A=1, B=2, C=3, D=4, which means that the shortest paths of A, B, C, D from the selected source vertex are 1, 2, 3, 4 respectively.

-For Prim's: A list of the = pairs separated by a comma. Example: B=A, C=B, D=A, which means that the parents of B, C, and D in the minimum spanning tree are A, B, and A respectively.

How to run -
Download the visualizer and algorithms repositories to your computer. Create a new project in IntelliJ IDEA, transfer the downloaded repositories to the `src` folder, and run the `ApplicationRunner` Java class.
