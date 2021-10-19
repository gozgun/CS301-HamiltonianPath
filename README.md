# CS301-HamiltonianAlgorithm

The problem we are considering in this project is 
«Given an n-node undirected graph G=(V,E), is there a simple path of edges in G that contains every node in V, and thus contains exactly n−1 edges?»

There is not an exact algorithm that solves Hamiltonian path problem in polynomial time. 
For instance, for a graph having N vertices, it visits all the permutations of the vertices (N! iterations). In each of those iterations, it traverses the permutation to see if adjacent vertices are connected or not, so the overall complexity is O(N * N!).

But there are some algorithms that finds if the Hamiltonian path exists or not in polynomial time. They will be an approximation to the exact solution.
In this project, we will cover and analyze the performance of a modified version of Kruskal algorithm.
