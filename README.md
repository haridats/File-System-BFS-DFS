File System Representation and Search Using BFS and DFS

1. Project Overview

This project implements a file system representation using a graph and an adjacency matrix in the C programming language. Each file or directory is represented as a node, and the connections between nodes are represented as directed edges.

The project uses Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms to search for a specified file or directory starting from a given node.

2. Objectives

- To represent a file system using a graph.
- To implement an adjacency matrix for graph representation.
- To implement Breadth-First Search (BFS).
- To implement Depth-First Search (DFS).
- To display the traversal order of both algorithms.
- To determine whether the specified file or directory is found.

3. Technologies Used

- Programming Language: C
- Data Structure: Graph
- Graph Representation: Adjacency Matrix
- Algorithms: BFS and DFS

4. Features

- Accepts file and directory names as nodes.
- Represents parent-child relationships using directed edges.
- Displays the adjacency matrix.
- Searches for a target node using BFS and DFS.
- Displays the traversal order of both algorithms.
- Reports whether the target file or directory is found.

5. Algorithms Used

Breadth-First Search (BFS)

BFS explores the graph level by level using a queue. It visits adjacent nodes before moving to nodes at the next level. In this project, BFS stops when the target node is found.

Depth-First Search (DFS)

DFS explores a path as deeply as possible before backtracking. This project implements DFS using recursion and stops when the target node is found.

6. Sample Input

The following input represents five nodes connected by four directed edges.

5
Root
Documents
Pictures
Notes
Photo
4
Root Documents
Root Pictures
Documents Notes
Pictures Photo
Root
Notes

7. Sample Output

Adjacency Matrix:
                  0   1   2   3   4
 0 Root           0   1   1   0   0
 1 Documents      0   0   0   1   0
 2 Pictures       0   0   0   0   1
 3 Notes          0   0   0   0   0
 4 Photo          0   0   0   0   0

--- Searching for 'Notes' starting from 'Root' ---

BFS Traversal Order: Root Documents Pictures Notes
BFS Result: File 'Notes' FOUND

DFS Traversal Order: Root Documents Notes
DFS Result: File 'Notes' FOUND

Note: The output above omits the input prompts for readability. The actual program displays these prompts while accepting input.

8. How to Compile and Run

Compile the program using GCC:

gcc main.c -o main

Run the program:

./main

9. Applications

- File and directory searching.
- Graph traversal and searching.
- Representation of hierarchical structures.
- Learning data structures and algorithms.
- Understanding BFS and DFS implementations in C.

10. Conclusion

This project demonstrates the representation of a file system as a graph using an adjacency matrix. BFS and DFS algorithms are implemented to traverse the graph and search for a specified file or directory. The project provides a practical understanding of graph representation, traversal techniques, queues, recursion, and searching algorithms in the C programming language.

Author

Name: Haridath S
College: UKF College of Engineering & Technology
Department: Cyber Security
Semester: Third Semester
Subject: Data Structures and Algorithms
