# Recursive depth first search

Given a list of all edges of a graph with vertices 1 to n, this algorithm will explore every vertex, depth first. Useful when exploring a small graph (depth < 300) as this algorithm is simpler and requires less space than the non-recursive dfs. Vertices are explored in lexicographic order.
Warning: will hit the python recursion limit if the graph is too large.



# Non-recursive depth first search

Given a list of all edges of a graph with vertices 1 to n, this algorithm will explore every vertex, depth first.
Useful when a large graph is to be explored, as the recursion limit on python is not a problem.
When exploring a smaller graph, consider using recursive dfs.
The order in which vertices are explored is not lexicographic



# Breadth first search

Given a list of edges of a graph with vertices 1 to n and a starting vertex, this algorithm will explore every vertex connected to the starting vertex breadth first using a queue.
