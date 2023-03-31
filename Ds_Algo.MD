Big O Notation Cheat Sheet
Big O Notation
Big O notation is used to describe the performance of an algorithm. It measures the worst-case scenario for how an algorithm will scale with input size.

O(1): constant time complexity (e.g. accessing an element in an array)
O(log n): logarithmic time complexity (e.g. binary search)
O(n): linear time complexity (e.g. iterating through an array)
O(n log n): log-linear time complexity (e.g. merge sort)
O(n^2): quadratic time complexity (e.g. nested loops)
O(2^n): exponential time complexity (e.g. brute force)
Data Structures
Data structures are used to store and organize data in memory. They can be classified as either primitive (built into the programming language) or abstract (implemented by the programmer).

Arrays
Contiguous block of memory
Random access by index
O(1) time complexity for access, insertion, and deletion at the end
O(n) time complexity for insertion and deletion at the beginning or middle
Linked Lists
Nodes with pointers to the next (and sometimes previous) node
No random access by index
O(1) time complexity for insertion and deletion at the beginning
O(n) time complexity for access, insertion, and deletion at the end or middle
Stacks
Last-in, first-out (LIFO) data structure
Implemented with arrays or linked lists
O(1) time complexity for push (insert) and pop (delete)
Queues
First-in, first-out (FIFO) data structure
Implemented with arrays or linked lists
O(1) time complexity for enqueue (insert) and dequeue (delete)
Trees
Hierarchical data structure with nodes and edges
Root node at the top, leaves at the bottom
Binary trees have at most two children per node
Traversal algorithms: depth-first search (pre-order, in-order, post-order) and breadth-first search
Hash Tables
Key-value pairs with a hash function for fast lookup
O(1) time complexity for access, insertion, and deletion on average (worst-case O(n))
Algorithms
Algorithms are step-by-step procedures for solving a problem.

Sorting
Bubble sort: O(n^2)
Selection sort: O(n^2)
Insertion sort: O(n^2)
Merge sort: O(n log n)
Quick sort: O(n log n) average, O(n^2) worst-case
Searching
Linear search: O(n)
Binary search: O(log n)
Graphs
Data structure with vertices and edges
Traversal algorithms: depth-first search and breadth-first search
I hope this cheat sheet helps you with your preparation for data structures and algorithms. Let me know if you have any other questions!
