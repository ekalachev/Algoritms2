# Algorithms, Part II by Princeton University

## Week 1:
- Underected graphs:
    - Task 1: Nonrecursive depth-first search. Implement depth-first search in an undirected graph without using recursion.
        - Hint 1: use an explicit stack.
        - Hint 2: it is trickier than it may appear at first; you can simply replace a queue with a stack in breadth-first search.
    - Task 2: Diameter and center of a tree. Given a connected graph with no cycles
        - Diameter: design a linear-time algorithm to find the longest simple path in the graph.
        - Center: design a linear-time algorithm to find a vertex such that its maximum distance from any other vertex is minimized.
        - Hint (diameter): to compute the diameter, pick a vertex ss; run BFS from ss; then run BFS again from the vertex that is furthest from ss.
        - Hint (center): consider vertices on the longest path.
    - Task 3: Euler cycle. An Euler cycle in a graph is a cycle (not necessarily simple) that uses every edge in the graph exactly one.
        - Show that a connected graph has an Euler cycle if and only if every vertex has even degree.
        - Design a linear-time algorithm to determine whether a graph has an Euler cycle, and if so, find one.
        - Hint: use depth-first search and piece together the cycles you discover.
