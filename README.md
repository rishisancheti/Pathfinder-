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

Single Source Shortest Path
The Single Source Shortest Path algorithm calculates the shortest (weighted) path from a node to all other nodes in the graph. Open Shortest Path First is a routing protocol for IP networks. It uses Single Source Shortest Path to detect changes in topology, such as link failures, and come up with a new routing structure in seconds.

Minimum Spanning Tree
The Minimum Weight Spanning Tree starts from a given node, and finds all its reachable nodes and the set of relationships that connect the nodes together with the minimum possible weight. It has the following use cases:

It was applied to analyze airline and sea connections of Papua New Guinea, and minimize the travel cost of exploring the country. It could be used to help design low-cost tours that visit many destinations across the country. More details can be found in "An Application of Minimum Spanning Trees to Travel Planning".

Analyzing and visualizing correlations in a network of currencies, based on the correlation between currency returns. This is described in "Minimum Spanning Tree Application in the Currency Market".

Tracing the history of transmission of infection in an outbreak supported by exhaustive clinical research. For more information, see Use of the Minimum Spanning Tree Model for Molecular Epidemiological Investigation of a Nosocomial Outbreak of Hepatitis C Virus Infection

Random Walk
Random Walk is an algorithm that provides random paths in a graph. A random walk means that we start at one node, choose a neighbor to navigate to at random or based on a provided probability distribution, and then do the same from that node, keeping the resulting path in a list. It’s similar to how a drunk person traverses a city. It has the following use cases:

It has be shown to relate to Brownian motion and also to the movement and dispersal of animals in the study of Random walk models in biology.

It has been used to analyse ALSI index of the JSE stock exchange and show that the index followed the random walk hypothesis between years 2000 and 2011. This means the movement of stock prices was random and the ability of investors to perform relied more on luck than anything else. Find this study in The Random Walk Theory And Stock Prices: Evidence From Johannesburg Stock Exchange

It is part of the node2vec and graph2vec algorithms, that create node embeddings, as well as the Walktrap and Infomap community detection algorithms.
