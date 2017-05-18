# Greedy Algorithms

This is a type of algorithmi in which problems are solved in a piecemeal manner in which each iteration the best piece is taken or used. Greedy algs. are usually used for optimization problems in which the problem can be broken down into pieces in which we can judge each piece then obtain the solution by taking the best piece for each iteration. If a greedy alg. finds the solution then it is generally the most optimal solution as it takes the largest "steps" possible toward the solution in each given iteration.

  :   # greedy1.c
  Takes in an array of (x,y) tuples representing the begin and end times for an
  event and outputs the the maximum number of events that can be completed. It
  sorts events by their end times and selects the event with the earliest end
  time then finds the next event with a start time greater or equal to the
  previously selected event. The optimal selection is printed out to terminal in
  tupal form (x,y)

  # greedy2.c
  Kruskal’s Minimum Spanning Tree Algorithm
  Given a connected and undirected graph this algorithm will search a minimum
  spanning tree of the graph which is a tree on the edges of the original graph
  of least weight.

  # greedy3.c
  Huffman Lossless Encoding

  # greedy4.c
  Knapsack problem using a greedy alg that takes the ratio of the value to weight
  to choose the optimal selection of items to pu in the knapsack.

  # greedy5.c
  Dijkstra's single shortest path algorithm for adjacency matrix of a graph
