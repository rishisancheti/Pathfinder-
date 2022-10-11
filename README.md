# Pathfinder-
Here's the project for path finder algorithm to find the shortest path 
 
 This Hacktoberfest 2022 lets Explore path finder algorithms to find the shortest path between two points .
 
 lets explore the pathfinding algorithms which help to solve real world Problems !
 
 What are path finding algorithms?

Pathfinding Algo Icon

Path finding algorithms build on top of graph search algorithms and explore routes between nodes, starting at one node and traversing through relationships until the destination has been reached. These algorithms find the cheapest path in terms of the number of hops or weight. Weights can be anything measured, such as time, distance, capacity, or cost

shortest Path

The Shortest Path algorithm calculates the shortest (weighted) path between a pair of nodes. Shortest path is considered to be one of the classical graph problems and has been researched as far back as the 19th century. It has the following use cases:

    Finding directions between physical locations. This is the most common usage, and web mapping tools such as Google Maps use the shortest path algorithm, or a variant of it, to provide driving directions.

    Social networks can use the algorithm to find the degrees of separation between people. For example, when you view someone’s profile on LinkedIn, it will indicate how many people separate you in the connections graph, as well as listing your mutual connections.

A*

The A* algorithm improves on the Dijkstra shortest path algorithm, by including extra information by way of a heuristic function that determines which paths to explore next. This optimization results in shortest paths being found more quickly. The A* algorithm can be used to find shortest paths between single pairs of locations, where GPS coordinates are known

Yen’s k-Shortest Paths
The Yen’s algorithm uses the shortest path algorithm to find the shortest path, 2nd shortest path, 3rd shortest path, and so on up to k-1 deviations of shortest path. It has the following use cases:

Optimizing multiple object tracking by formalizing the motions of targets as flows along the relationships of the spatial graph. Find more in Multiple Object Tracking using K-Shortest Paths Optimization

Studying alternative routing on road networks and to recommend top k-paths to the user. Find this study in Alternative Routing: k-Shortest Paths with Limited Overlap

Part of the Finding Diverse High-Quality Plans for Hypothesis Generation process.

All-Pairs Shortest Path
The All Pairs Shortest Path calculates the shortest (weighted) path between all pairs of nodes. This algorithm has optimizations that make it quicker than calling the Single Source Shortest Path algorithm for every pair of nodes in the graph. It has the following use cases:

Itis used in urban service system problems, such as the location of urban facilities or the distribution or delivery of goods. One example of this is determining the traffic load expected on different segments of a transportation grid. For more information, see Urban Operations Research.

It is used as part of the REWIRE data center design algorithm that finds a network with maximum bandwidth and minimal latency. There are more details about this approach in "REWIRE: An Optimization-based Framework for Data Center Network Design"
