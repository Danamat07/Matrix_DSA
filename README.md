# Matrix_DSA
ADT Matrix – represented as a sparse matrix with tuples of the form (row, column, value) (value ≠ 0), where the tuples are stored in lexicographical order by (row, column) in a binary search tree (BST) with a linked representation and dynamic allocation. The project includes both short and extended tests.

This project implements an ADT Matrix in C++, represented as a sparse matrix using tuples of the form (row, column, value) where the value is not equal to zero. The matrix is stored in a binary search tree (BST), with the tuples arranged in lexicographical order by (row, column). The tree uses a linked representation with dynamic allocation.

Files in the Project
  - App.cpp: The main application file that demonstrates the usage of the Matrix and tests its functionality.
  - ExtendedTest.cpp: Contains extended test cases to verify the correctness and performance of the Matrix data structure.
  - ExtendedTest.h: Header file for the extended test cases, defining test functions for larger and edge cases.
  - ShortTest.cpp: Contains short test cases to check basic functionality and correctness of the Matrix.
  - ShortTest.h: Header file for the short test cases, declaring functions to test basic operations on the Matrix.
  - Matrix.cpp: The implementation of the Matrix class, which stores the non-zero values in a sparse matrix using a binary search tree (BST).
  - Matrix.h: Header file for the Matrix class, providing declarations for its methods and attributes. The structure of the nodes used in the BST is also defined here.

NOTE: The code for this project can be found on the master branch.
