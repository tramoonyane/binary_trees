# C - Binary Trees

## Overview

This repository contains C programs related to Binary Trees, demonstrating various functionalities, operations, and concepts associated with binary tree data structures in C.

## What is a Binary Tree?

A binary tree is a hierarchical data structure composed of nodes, where each node has at most two children: a left child and a right child. It starts with a root node and branches out, forming a tree-like structure.

## Difference between a Binary Tree and a Binary Search Tree (BST)

The main difference lies in how the elements/nodes are organized. While both are binary trees, a Binary Search Tree (BST) maintains a specific order where the left child of a node contains elements smaller than the node, and the right child contains elements greater than the node.

## Time Complexity Gain Compared to Linked Lists

Compared to linked lists, binary trees provide faster search, insertion, and deletion operations in certain scenarios. The time complexity for these operations in a balanced binary tree is O(log n), whereas in linked lists, it's O(n) for search and O(1) for insertion/deletion at the beginning (with sequential search).

## Characteristics of a Binary Tree

- **Depth**: The depth of a node is the number of edges from the root to that node.
- **Height**: The height of a tree is the length of the longest path from the root node to any leaf node.
- **Size**: The size of a binary tree is the total number of nodes present in the tree.

## Traversal Methods in a Binary Tree

There are three main traversal methods:
- **Inorder**: Visit left subtree, then the root, then the right subtree.
- **Preorder**: Visit the root, then the left subtree, then the right subtree.
- **Postorder**: Visit left subtree, then the right subtree, then the root.

## Types of Binary Trees

- **Complete Binary Tree**: Every level except the last is completely filled, and all nodes are as left as possible.
- **Full Binary Tree**: Every node has either 0 or 2 children.
- **Perfect Binary Tree**: All interior nodes have two children, and all leaves have the same depth.
- **Balanced Binary Tree**: The height difference between left and right subtrees for every node is not more than one, maintaining balance.

Feel free to explore the programs in this repository to understand and experiment with various operations on binary trees in C.
