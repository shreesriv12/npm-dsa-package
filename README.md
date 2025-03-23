# npm-dsa-package
📦 DSA-Utils
A comprehensive JavaScript library implementing fundamental, advanced, and concurrent data structures for efficient and reusable programming. This package provides easy-to-use and well-tested implementations of arrays, linked lists, trees, graphs, heaps, hash tables, and more.

🚀 Features
✅ Wide range of data structures categorized into:

Basic: Array, Linked List, Stack, Queue, etc.

Trees: Binary Tree, AVL Tree, Red-Black Tree, Trie, Segment Tree, etc.

Graphs: Adjacency List, Directed Graph, Weighted Graph, Spanning Tree, etc.

Hash-based: Hash Table, Bloom Filter, Cuckoo Filter, etc.

Advanced: Disjoint Set, Skip List, Merkle Tree, Van Emde Boas Tree, etc.

Special-purpose: LRU Cache, LFU Cache, Circular Buffer, Count-Min Sketch, etc.

Concurrent: Concurrent Hash Map, Lock-free Data Structures, etc.

✅ Clean and modular code structure
✅ Well-tested with Jest
✅ Easy-to-use APIs
✅ Ready for production use

🔧 Installation
Install the package using npm:

bash
Copy
Edit
npm install dsa-utils
Or using yarn:

bash
Copy
Edit
yarn add dsa-utils
📚 Usage
💡 Basic Data Structures
Array
javascript
Copy
Edit
const { DSAArray } = require('dsa-utils');

const arr = new DSAArray();
arr.push(10);
arr.push(20);
console.log(arr.get(0));  // Output: 10
console.log(arr.size());   // Output: 2
Stack
javascript
Copy
Edit
const { Stack } = require('dsa-utils');

const stack = new Stack();
stack.push(1);
stack.push(2);
console.log(stack.pop());   // Output: 2
🌳 Tree Data Structures
Binary Search Tree (BST)
javascript
Copy
Edit
const { BST } = require('dsa-utils');

const bst = new BST();
bst.insert(10);
bst.insert(5);
bst.insert(15);
bst.inOrder();  // Output: 5, 10, 15
AVL Tree
javascript
Copy
Edit
const { AVLTree } = require('dsa-utils');

const avl = new AVLTree();
avl.insert(10);
avl.insert(20);
avl.insert(30);
avl.display();  // Balanced tree
🔗 Graph Data Structures
Adjacency List
javascript
Copy
Edit
const { Graph } = require('dsa-utils');

const graph = new Graph();
graph.addVertex('A');
graph.addVertex('B');
graph.addEdge('A', 'B');
graph.display();
🛠️ Advanced Data Structures
Disjoint Set (Union-Find)
javascript
Copy
Edit
const { DisjointSet } = require('dsa-utils');

const ds = new DisjointSet(5);
ds.union(1, 2);
console.log(ds.find(1));  // Output: representative element
Skip List
javascript
Copy
Edit
const { SkipList } = require('dsa-utils');

const skipList = new SkipList();
skipList.insert(10);
skipList.insert(20);
console.log(skipList.search(20));  // Output: true
🔥 Special-Purpose Data Structures
LRU Cache
javascript
Copy
Edit
const { LRUCache } = require('dsa-utils');

const cache = new LRUCache(3);
cache.put(1, "A");
cache.put(2, "B");
cache.put(3, "C");
cache.get(1);  // Returns "A"
cache.put(4, "D");  // Removes least recently used item
🧑‍🏫 API Reference
Basic Data Structures
Structure	Methods	Description
Array	push(), pop(), get(), size()	Basic dynamic array
Stack	push(), pop(), peek()	LIFO data structure
Queue	enqueue(), dequeue()	FIFO data structure
PriorityQueue	enqueue(), dequeue()	Queue with priority
Deque	pushFront(), pushBack()	Double-ended queue
CircularQueue	enqueue(), dequeue()	Circular queue with fixed capacity
Tree Data Structures
Structure	Methods	Description
BST	insert(), inOrder()	Binary Search Tree
AVLTree	insert(), display()	Balanced AVL Tree
RedBlackTree	insert(), delete()	Red-Black Tree
Trie	insert(), search()	Prefix tree
SegmentTree	build(), query()	Range-based tree
MinHeap	insert(), extractMin()	Min-Heap
🧪 Running Tests
The package includes test cases for all data structures using Jest.

To run tests:

bash
Copy
Edit
npm test
📦 Project Structure
bash
Copy
Edit
/src                      → Data structures source code  
/__tests__                 → Unit tests for all structures  
/index.js                  → Main entry point  
/package.json               → NPM configuration  
/README.md                  → Documentation  
/LICENSE                    → License  
✅ Contributing
Contributions are welcome!
To contribute:

Fork the repository

Create a new branch (git checkout -b feature/your-feature)

Commit your changes (git commit -m 'Add feature')

Push to the branch (git push origin feature/your-feature)

Open a pull request

📄 License
This project is licensed under the MIT License.

🚀 Future Enhancements
Algorithm visualizer: Add visualizations for sorting, searching, and graph algorithms

TypeScript support: Enhance the package with full TypeScript compatibility

CLI tool: Add a CLI interface for executing data structure operations

📫 Contact
For any queries or feedback, feel free to reach out:

Email: shreeyasrivastava1124@gmail.com

GitHub: shreesriv12
