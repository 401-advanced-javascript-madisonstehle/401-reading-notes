# Class-30
## DSA: Graphs

### Links
- [Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)


### Discussion
#### Vocabulary
- **Vertex**: A node. It's a data object that can have zero or more adjacent vertices
- **Edge**: A connection between two nodes
- **Neighbor**: The adjacent nodes to a node connected with an edge
- **Degree**: The number of edges connected to that vertex

#### Graph Directions
- **Undirected Graph**: Each edge is bi-directional or _undirected_, and the graph does not move in any direction.
- **Directed Graph**: Also called a `Digraph`. Every edge is directed to somewhere. This type of graph has a direction.
- **Acyclic**: A directed graph without _cycles_ (a cycle is when a node can be traversed through and potentially end up back at itself). These can be referred to as a DAG (Directed Acyclic Graph) and can be represented by a `tree`.
- **Cyclic**: A graph that has cycles. Defined as a path of a positive length that starts and ends at the same vertex.

#### Types of Graphs
- **Complete**: All nodes are connected to all other nodes.
- **Connected**: All `vertices`/`nodes` have at least one edge.
- **Disconnected**: Some vertices may not have edges.

#### Representation
- **Adjacency Matrix**: Represented through a 2-dimensional array where each row and column represents each vertex of the data structure.
- **Adjacency List**: A collection of linked lists or array that lists all of the other vertices that are connected.



#### [Back to Home](README.md)