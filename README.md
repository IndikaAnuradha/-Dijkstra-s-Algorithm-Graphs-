# Dijkstra's-Algorithm-Graphs-
Dijkstra’s algorithm is an algorithm (a set of instructions with which we can give a solution to a problem) used in a graph. It was conceived in 1956 by Edsger. W Dijkstra to solve the problem of finding the shortest paths between nodes in a graph.
Dijkstra’s Algorithm is a classic graph search algorithm that finds the shortest path from a source node to all other nodes in a weighted graph with non-negative edge weights.

:eight_pointed_black_star: Key Idea:
It incrementally builds the shortest path by always choosing the closest unvisited node, updating the cost of its neighbors, and marking it as visited.

:eight_pointed_black_star: Algorithm Steps:

:black_medium_square: Initialize distances to all nodes as infinity, except the source (set to 0).

:black_medium_square: Use a priority queue (or min-heap) to repeatedly select the unvisited node with the smallest known distance.

:black_medium_square: Relax edges: for each neighbor, update its distance if a shorter path is found.

:black_medium_square: Continue until all nodes have been visited or the shortest path to the target is found.

![MQTT](https://github.com/IndikaAnuradha/MQTT-publisher-implementation-in-Python/assets/122884553/8bed5399-9fb2-4934-9800-457e7eabae21)


