# Data Structures Crash Course

## Contents

- [Binary Tree](#binary-tree)
- [Heaps](#heaps)
- [Graphs](#graphs)

## Binary Tree

- **Binary Tree:** Each node can have 0, 1 or 2 nodes.

- **Perfect Binary tree(efficient):** a binary tree in which all interior nodes have two children and all leaves have the same depth or same level.

  **Properties:**

  - The number of nodes doubles at each level.
  - **Number of nodes in the last level** = (Number of nodes in the previous levels + 1).
  - **Total number of nodes** = 2<sup>h</sup> - 1, where h = height of binary tree.

- **Full Binary Tree:** a tree in which every node other than the leaves has exactly zero or two children.

- **Applications:**

  - O(logn) : Search Engines

- **BST:**

  - subset of binary tree,
  - helps us establish relationship with parent
  - right subtree has values greater than parent
  - left subtree has values lesser than parent

- **Pros of BST:**

  - better than O(n).
  - ordered.
  - flexible size.

- **Cons:**

  - no O(1) operations.

- **Operations:** All Operations(O(logn))

  - insert()
  - lookup()
  - remove()

- **Balanced vs Unbalanced BST:**

  - **Unbalanced:** Nodes get added only to one side like a linked list. this affects performance.

- **AVL trees + Red black trees:** For balancing BST.

  - **AVL Trees:**

    - Animation: https://www.cs.usfca.edu/~galles/visualization/AVLtree.html
    - How it Works: https://medium.com/basecs/the-little-avl-tree-that-could-86a3cae410c7

  - **Red Black Trees:**

    - Animation: https://www.cs.usfca.edu/~galles/visualization/RedBlack.html
    - How it Works: https://medium.com/basecs/painting-nodes-black-with-red-black-trees-60eacb2be9a5

  - Technical differences between AVL and Red Black Tree: https://stackoverflow.com/questions/13852870/red-black-tree-over-avl-tree

  - **Trie:** Searching for words in dictionary.
    - **Applications:** Autocomplete
    - **lookup:** O(length of the word)

## Heaps

- Also known as binary heaps.
- It has properties of a perfect binary tree.
  - **max heap:** all parent nodes have higher value than child nodes.
  - **min heap:** all parent nodes have lesser value than child nodes.
- **Traversal:** O(n), because unlike BST there is no meaning between left and right child.
- **Insert and Delete:** O(logn)

- **Pros:**

  - Good at doing comparitive operations: say values > 55.
  - Bubbles up while inserting if needed.
  - No unbalanced scenario.
  - Fast insert, priority, flexible size, better than O(n).

- **Cons:**

  - Slow lookup

- **Priority Queues != Queues:**
  - Priority Queues != Queues
  - Implemented using binary heaps.
  - Elements will be given importance based on priority.

## Graphs

- **Graphs:** has vertices and edges.

- **Types:** (&#128161; Some types also denote difference between trees and graphs.)

  - directed(unidirectional) or undirected.
  - unweighted or weighted.
  - cyclic or acyclic.

- **Graph Representations:**

  - **Resource:** https://www.khanacademy.org/computing/computer-science/algorithms/graph-representation/a/representing-graphs
  - edge list
  - adjacent list
  - adjacency matrix

- **Pros:**

  - relationships

- **Cons:**

  - hard to scale
