# 📚 DSA Package

### 🚀 A comprehensive package for Data Structures and Algorithms implemented in C++ and Python.

---

## ⚙️ **Features**

### 🔥 **Data Structures**
- **Arrays:** Insertion, Deletion, Searching, and Sorting.
- **Linked Lists:** 
  - Singly, Doubly, and Circular Linked Lists.
  - Operations: Insertion, Deletion, Reversal, and Sorting.
- **Stacks and Queues:** 
  - Push, Pop, Peek operations.
  - Circular Queue, Deque, and Priority Queue.
- **Trees:** 
  - Binary Tree, Binary Search Tree (BST), AVL Tree, Red-Black Tree.
  - Tree Traversals: Inorder, Preorder, Postorder, and Level-order.
- **Graphs:** 
  - Adjacency List and Matrix representation.
  - BFS (Breadth-First Search) and DFS (Depth-First Search).
  - Dijkstra’s and Floyd-Warshall’s algorithms.
- **Heaps:**
  - Min-Heap and Max-Heap.
  - Heap Sort and Priority Queue.

---

### ⚡️ **Algorithms**
- **Searching Algorithms:**
  - Linear Search, Binary Search, Jump Search, Interpolation Search.
- **Sorting Algorithms:**
  - Bubble Sort, Selection Sort, Insertion Sort.
  - Merge Sort, Quick Sort, Heap Sort, Radix Sort.
- **Dynamic Programming (DP):**
  - Fibonacci Series, Knapsack Problem, Longest Common Subsequence (LCS).
- **Greedy Algorithms:**
  - Fractional Knapsack, Activity Selection.
- **Backtracking:**
  - N-Queens Problem, Sudoku Solver, Subset Sum.
- **Recursion and Divide & Conquer:**
  - Factorial, Tower of Hanoi, Merge Sort.
- **Bit Manipulation Algorithms:**
  - Check Even/Odd, Count Set Bits, Power of Two.

---

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

### 📚 Usage
C++ Example: Linked List
````
#include "dsa/linked_list.h"

int main() {
    LinkedList list;
    list.insert(10);
    list.insert(20);
    list.display();
    return 0;
}
````

###Python Example: Stack
```
from dsa.stack import Stack

stack = Stack()
stack.push(10)
stack.push(20)
print(stack.pop())  # Output: 20
```

For Python:
Run the test cases using pytest:
pytest tests/

For C++:
Compile and run the test files:
g++ -o test test.cpp && ./test

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

## 📊 **Visualization**

For sorting and tree traversals, you can include visualizations using **Matplotlib (Python)** or **Graphviz (C++)**.

---

### 🐍 **Python Visualization Example**
You can visualize data using **Matplotlib** by running the following code:
```python
import matplotlib.pyplot as plt

# Sample data
data = [5, 2, 9, 1, 5, 6]

# Plotting a bar chart
plt.bar(range(len(data)), data)
plt.title("Sample Visualization")
plt.xlabel("Index")
plt.ylabel("Value")
plt.show()
````


## 🛡️ **Contributing**
Contributions are welcome! If you'd like to contribute:

1. **Fork** the repository.
2. **Create a new branch**.
3. **Commit your changes**.
4. **Open a pull request**.


---

## 🚀 **Future Improvements**
Planned enhancements for this project include:
- ✅ Add **Trie** and **HashMap** data structures.
- ✅ Implement **Kruskal’s** and **Prim’s algorithms** for Minimum Spanning Tree (MST).
- ✅ Add **Graphical Visualization** for traversals and sorting.
- ✅ Include **Leetcode-style problems** for DSA practice.

---

## 📄 **License**
This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute it under the terms of the license.

---

## 📬 **Contact**
For any issues or suggestions, reach out at:

- **Email:** shreeyasrivastava1124@gmail.com  
- **GitHub:** shreesriv12

---







