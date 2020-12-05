# Data Structures Crash Course

## Contents

- [Binary Tree](#binary-tree)

## Binary Tree

- **Binary Tree:** Each node can have 0, 1 or 2 nodes.

- **Perfect Binary tree(efficient):** a binary tree in which all interior nodes have two children and all leaves have the same depth or same level.

  **Properties:**

  - The number of nodes doubles at each level.
  - **Number of nodes in the last level** = (Number of nodes in the previous levels + 1).
  - **Total number of nodes** = 2<sup>h</sup> - 1, where h = height of binary tree.

- **Full Binary Tree:** a tree in which every node other than the leaves has exactly zero or two children.

## Graphs

- **Graphs:** has vertices and edges.

- **Types:** (&#128161; Some types also denote difference between trees and graphs.)

  - directed(unidirectional) or undirected.
  - unweighted or weighted.
  - cyclic or acyclic.

- **Graph Representations:**

  - edge list
  - adjacent list
  - adjacency matrix

- **Pros:**

  - relationships

- **Cons:**

  - hard to scale
