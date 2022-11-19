# Shortest-path-using-parallel-programming
Four algorithms discussed with the most efficient route parallel algorithm.

ABSTRACT : 

Roads play a major role in the lives of people living in various states, cities, towns and villages. From their daily travel to work, to schools, to business meetings, to the transport of goods and enablement of services, roads play major role in facilitating rural and urban life. In this modern era, where roads have been laid down in the most remote locations, they prove to be one of the most useful mediums for transportation and travel. The manipulation of shortest paths between various locations sometimes proves to be tricky when dealing with complex road networks. Dijkstra's Algorithm is used to overcome the problem of finding shortest path. The main objective of this algorithm is to find shortest path between two points or nodes in any network with minimum cost implementation. Dijkstra algorithm overcomes the drawbacks of Floyd Warshall Algorithm as well as Bellman Ford Algorithm but it can be improvised if we implement it parallelly. Hence, in this project we will try to improvise the algorithm using parallel computing. 

PROBLEM STATEMENT : 

Roads have been laid down in the most remote locations and they prove to be one of the most useful mediums for transportation and travel. But due to environmental factors and nature of the transport, drivers face enormous hurdles and usually have to travel more than necessary.  Devising a method to properly plan out routes and stops for efficient delivery will help to reduce stress on drivers and benefit the transport company as well as the client since deliveries will take less time and can be made more frequently.

INTRODUCTION : 

Dijkstra's Algorithm is used to overcome the problem of finding shortest path. The main objective of this algorithm is to find shortest path between two points or nodes in any network with minimum cost implementation. Dijkstra algorithm overcomes the drawbacks of Floyd Warshall Algorithm as well as Bellman Ford Algorithm but it can be improvised if we implement it parallelly. Hence, in this project we will try to improvise the algorithm using parallel computing.

OBJECTIVES

1-Show how Dijkstra’s Algorithm is better than Floyd Warshall   Algorithm  and Bellman Ford Algorithm.

2-Implement Dijkstra Algorithm using Parallel Computing.

3-Show how proposed algorithm is better than the previous one.

METHODOLOGY : 

Our main focus in this project is to reduce the time taken during the transportation of goods or public transport. For traversing all the destination points we are using an algorithm called Dijkstra’s Algorithm which calculates the shortest paths to all points.
Dijkstra algorithm overcomes the drawbacks of Floyd Warshall Algorithm as well as Bellman Ford Algorithm but it can be improvised if we implement it parallelly. Hence, in this project we will try to improvise the algorithm using parallel computing.

CONCLUSION : 

Parallel programming is a very intricate, yet increasingly important task as we have entered the multicore era and more cores are made available to the programmer going from dual core to 32 and 64 core systems or super computers. Independent tasks within a single application can be easily mapped on multicore platforms, the same is not true for applications that do not expose parallelism in a straightforward way. 
According to the results achieved, Bellman Ford algorithm is a challenging example of such an algorithm that is difficult to accelerate when executed in a multithreaded fashion because of its complexity being O(n3 ) . It is very important to have in mind the two major issues inherent to Bellman Ford algorithm: limited independent tasks and excessive synchronization. 
There are several possible reasons why the parallel execution of algorithms wasn't as fast as expected for smaller number of nodes. One of the reasons could be that the code used may be inefficient. Another possibility is that, for a small amount of nodes, more time could be spent on parallelization and synchronization then it is spent on execution of code as sequential.
Our project report infers that in the efficient transportation system there should be shortest path as well as clean path with no complications in bellman ford and Floyd warshall we see major drawbacks like huge execution time as well as limited independent task . So the Dijkstra set a major foot over them and can be seen as the most efficient solution for the real world applications like transportation system. 






