# 📚 DSA Package

### 🚀 A comprehensive package for Data Structures and Algorithms implemented in C++ and Python.

---

## ⚙️ **Features**

### 🔥 **Data Structures**
Data Structures
---------------

### Arrays

*   **Operations**: Insertion, Deletion, Searching, Sorting
    
*   **Time Complexity**:
    
    *   Access: O(1)
        
    *   Search: O(n) for linear search, O(log n) for binary search (if sorted)
        
    *   Insertion/Deletion: O(n) (may require shifting elements)
        

### Linked Lists

*   **Types**:
    
    *   Singly Linked Lists
        
    *   Doubly Linked Lists
        
    *   Circular Linked Lists
        
*   **Operations**: Insertion, Deletion, Reversal, Sorting
    
*   **Time Complexity**:
    
    *   Access: O(n)
        
    *   Search: O(n)
        
    *   Insertion/Deletion: O(1) (with pointer access)
        

### Stacks and Queues

*   **Stack Operations**: Push, Pop, Peek (LIFO - Last In First Out)
    
*   **Queue Operations**: Enqueue, Dequeue, Front (FIFO - First In First Out)
    
*   **Variations**:
    
    *   Circular Queue
        
    *   Deque (Double-ended Queue)
        
    *   Priority Queue
        
*   **Applications**: Function calls, Undo operations, Breadth-first search, Task scheduling
    

### Trees

*   **Types**:
    
    *   Binary Tree
        
    *   Binary Search Tree (BST)
        
    *   AVL Tree (Self-balancing)
        
    *   Red-Black Tree (Self-balancing)
        
    *   B-Tree and B+ Tree (Disk-based, used in databases)
        
*   **Traversals**:
    
    *   Inorder (Left-Root-Right)
        
    *   Preorder (Root-Left-Right)
        
    *   Postorder (Left-Right-Root)
        
    *   Level-order (Breadth-first)
        
*   **Operations**: Insert, Delete, Search, Balance
    
*   **Applications**: Database indexing, Expression evaluation, File systems
    

### Heaps

*   **Types**:
    
    *   Min-Heap (parent smaller than children)
        
    *   Max-Heap (parent larger than children)
        
*   **Operations**: Insert, Delete, Extract-min/max, Heapify
    
*   **Applications**: Heap Sort, Priority Queues, Selection algorithms
    

### Graphs

*   **Representations**:
    
    *   Adjacency Matrix
        
    *   Adjacency List
        
*   **Algorithms**:
    
    *   BFS (Breadth-First Search)
        
    *   DFS (Depth-First Search)
        
    *   Dijkstra's (Shortest Path)
        
    *   Floyd-Warshall (All-Pairs Shortest Path)
        
    *   Prim's and Kruskal's (Minimum Spanning Tree)
        
    *   Topological Sort
        
    *   Strongly Connected Components
        
*   **Applications**: Social networks, Maps/Navigation, Network routing
    

### Hash Tables/Maps

*   **Implementation**:
    
    *   Separate Chaining
        
    *   Open Addressing
        
*   **Collision Resolution**:
    
    *   Linear Probing
        
    *   Quadratic Probing
        
    *   Double Hashing
        
*   **Operations**: Insert, Delete, Search
    
*   **Time Complexity**: O(1) average case for all operations
    
*   **Applications**: Databases, Caches, Symbol tables
    

### Trie (Prefix Tree)

*   **Operations**: Insert, Search, Delete
    
*   **Variations**: Compressed Trie, Suffix Tree, Suffix Array
    
*   **Applications**: Autocomplete, Spell checking, IP routing
    

### Disjoint Set (Union-Find)

*   **Operations**: Find, Union
    
*   **Optimizations**: Path Compression, Union by Rank/Size
    
*   **Applications**: Kruskal's algorithm, Network connectivity, Image processing
    

### Segment Trees & Fenwick Trees

*   **Operations**: Range queries (Sum, Min, Max), Point updates
    
*   **Applications**: Range query problems, Computational geometry
    

Algorithms
----------

### Searching Algorithms

*   **Linear Search**: O(n)
    
*   **Binary Search**: O(log n)
    
*   **Jump Search**: O(√n)
    
*   **Interpolation Search**: O(log log n) average case
    

### Sorting Algorithms

*   **Comparison-Based**:
    
    *   Bubble Sort: O(n²)
        
    *   Selection Sort: O(n²)
        
    *   Insertion Sort: O(n²)
        
    *   Merge Sort: O(n log n)
        
    *   Quick Sort: O(n log n) average, O(n²) worst
        
    *   Heap Sort: O(n log n)
        
*   **Non-Comparison Based**:
    
    *   Counting Sort: O(n+k)
        
    *   Radix Sort: O(d(n+k))
        
    *   Bucket Sort: O(n+k)
        

### Dynamic Programming (DP)

*   **Concept**: Breaking complex problems into simpler subproblems
    
*   **Applications**:
    
    *   Fibonacci Series
        
    *   Knapsack Problem
        
    *   Longest Common Subsequence (LCS)
        
    *   Longest Increasing Subsequence
        
    *   Matrix Chain Multiplication
        
    *   Edit Distance
        

### Greedy Algorithms

*   **Concept**: Making locally optimal choices at each stage
    
*   **Examples**:
    
    *   Fractional Knapsack
        
    *   Activity Selection
        
    *   Huffman Coding
        
    *   Dijkstra's Algorithm
        
    *   Prim's and Kruskal's Algorithm
        

### Backtracking

*   **Concept**: Building solutions incrementally and abandoning when they fail to satisfy constraints
    
*   **Applications**:
    
    *   N-Queens Problem
        
    *   Sudoku Solver
        
    *   Subset Sum
        
    *   Hamiltonian Path
        
    *   Graph Coloring
        

### Recursion and Divide & Conquer

*   **Examples**:
    
    *   Factorial Calculation
        
    *   Tower of Hanoi
        
    *   Merge Sort
        
    *   Quick Sort
        
    *   Binary Search
        
    *   Strassen's Matrix Multiplication
        

### Bit Manipulation Algorithms

*   **Operations**:
    
    *   Check Even/Odd
        
    *   Count Set Bits
        
    *   Test if Power of Two
        
    *   Set/Clear/Toggle Bit
        
    *   Bit Masking
        

### String Algorithms

*   **Pattern Matching**:
    
    *   Knuth-Morris-Pratt (KMP)
        
    *   Rabin-Karp
        
    *   Boyer-Moore
        
*   **Advanced String Problems**:
    
    *   Longest Palindromic Substring
        
    *   Edit Distance
        
    *   String Compression
        

### Advanced Graph Algorithms

*   **Network Flow**:
    
    *   Ford-Fulkerson
        
    *   Edmonds-Karp
        
    *   Dinic's Algorithm
        
*   **Maximum Bipartite Matching**
    
*   **Minimum Cut**
    

### Computational Geometry

*   **Convex Hull**: Graham Scan, Jarvis March
    
*   **Line Intersection**
    
*   **Point in Polygon**
    
*   **Closest Pair of Points**
    

### Randomized Algorithms

*   **Quickselect** (Finding the kth smallest element)
    
*   **Random Pivot Selection** in Quick Sort
    
*   **Monte Carlo and Las Vegas Algorithms**
    

### Approximation Algorithms

*   **NP-Hard Problems**:
    
    *   Traveling Salesman Problem approximations
        
    *   Set Cover
        
    *   Vertex Cover
        
    *   Knapsack Problem approximation
        

### Number Theory Algorithms

*   **Primality Testing**
    
*   **Greatest Common Divisor (GCD)**
    
*   **Least Common Multiple (LCM)**
    
*   **Modular Exponentiation**
    
*   **Sieve of Eratosthenes**
    

Application Areas
-----------------

*   **Competitive Programming**
    
*   **Technical Interviews**
    
*   **System Design**
    
*   **Machine Learning Algorithms**
    
*   **Database Management Systems**
    
*   **Operating Systems**
    
*   **Computer Networks**
    


Implementation Guidelines
-------------------------

*   Time and Space Complexity Analysis
    
*   Choosing the Right Data Structure
    
*   Algorithm Design Techniques
    
*   Testing and Debugging Strategies

## 🛠️ **Installation**

### **Clone the repository:**

git clone https://github.com/shreesriv12/npm-dsa-package.git
cd dsa-package


## ⚙️ **Install Dependencies**

### 🐍 **For Python**
Install the required Python libraries by running:
```bash
pip install -r requirements.txt
```
###  **For C++**
```
g++ -o main main.cpp && ./main
```



## 📊 **Complexity Analysis**

### 🛠️ **Time and Space Complexities for Common Algorithms**

| **Algorithm**         | **Time Complexity**         | **Space Complexity**        |
|------------------------|-----------------------------|-----------------------------|
| **Linear Search**      | \( O(n) \)                  | \( O(1) \)                  |
| **Binary Search**      | \( O(\log n) \)              | \( O(1) \)                  |
| **Bubble Sort**        | \( O(n^2) \)                 | \( O(1) \)                  |
| **Quick Sort**         | \( O(n \log n) \)            | \( O(\log n) \)              |
| **Merge Sort**         | \( O(n \log n) \)            | \( O(n) \)                   |
| **Dijkstra's Algorithm**| \( O(V + E \log V) \)       | \( O(V + E) \)               |
| **BFS** (Breadth-First Search) | \( O(V + E) \)         | \( O(V) \)                   |
| **DFS** (Depth-First Search)   | \( O(V + E) \)         | \( O(V) \)                   |

---



## 🛡️ **Contributing**
Contributions are welcome! If you'd like to contribute:

1. **Fork** the repository.
2. **Create a new branch**.
3. **Commit your changes**.
4. **Open a pull request**.



## 📄 **License**
This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute it under the terms of the license.

---

## 📬 **Contact**
For any issues or suggestions, reach out at:

- **Email:** shreeyasrivastava1124@gmail.com  
- **GitHub:** shreesriv12

---







