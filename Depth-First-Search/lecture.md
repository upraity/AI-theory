# Depth First Search

Depth-first search is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking, then backtracks until it finds an unexplored path, and then explores it. The algorithm does this until the entire graph has been explored. Many problems in computer science can be thought of in terms of graphs.
For example, analyzing networks, mapping routes, scheduling, and finding spanning trees are graph problems. To analyze these problems, graph-search algorithmlike depth-first search are useful.

# Algorithm

1. Enter (PUSH) root node on stack .

2. Do until stack is empty:
    - Remove (POP) node.
        -  if node is gool node stop.
        -  push all children node in stack.

# Advantages and Disadvantages of Depth First Search Algorithm

## Advantages

- Less time and space complexity rather then BSF .
- Less memory requirement becouse it only stores stack of nodes on the path from root node to current node.
- Less time to reach the goal node.

## Disadvantages

- No guaranteed that it will give you a solution .
- Depth is infinite then finding the solution is more complex .


> by- _Tarun Kumar Sharma_
