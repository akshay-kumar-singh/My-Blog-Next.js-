---
title: Important DSA question
excerpt: DSA stands for data structure and algorithm. You probably don't know it well enough!
image: dsa.png
isFeatured: false
date: '2021-10-30'
---

DATA STRUCTURE & ALGORITHM


**Basic Data Structure Interview Questions for Freshers**

1. **What are Data Structures?**

A data structure is a mechanical or logical way that data is organized within a program. The organization of data is what determines how a program performs. There are many types of data structures, each with its own uses. When designing code, we need to pay particular attention to the way data is structured. If data isn't stored efficiently or correctly structured, then the overall performance of the code will be reduced.

![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.001.png)

**Create A Free Personalised Study Plan**

Get into your dream companies with expert guidance

2. **Why Create Data Structures?**

Data structures serve a number of important functions in a program. They ensure that each line of code performs its function correctly and efficiently, they help the programmer identify and fix problems with his/her code, and they help to create a clear and organized code base.

3. **What are some applications of Data structures?**

Following are some real-time applications of data structures:

- Decision Making
- Genetics
- Image Processing
- Blockchain
- Numerical and Statistical Analysis
- Compiler Design
- Database Design and many more![ref1]
4. **Explain the process behind storing a variable in memory.**
- A variable is stored in memory based on the amount of memory that is needed. Following are the steps followed to store a variable:
  - The required amount of memory is assigned first.
  - Then, it is stored based on the data structure being used.
- Using concepts like dynamic allocation ensures high efficiency and that the storage units can be accessed based on requirements in real-time.
5. **Can you explain the difference between file structure and storage structure?**
- File Structure: Representation of data into secondary or auxiliary memory say any device such as a hard disk or pen drives that stores data which remains intact until manually deleted is known as a file structure representation.
- Storage Structure: In this type, data is stored in the main memory i.e RAM, and is deleted once the function that uses this data gets completely executed.

The difference is that the storage structure has data stored in the memory of the computer system, whereas the file structure has the data stored in the auxiliary memory.

6. **Describe the types of Data Structures?**
- Linear Data Structure: A data structure that includes data elements arranged sequentially or linearly, where each element is connected to its previous and next nearest elements, is referred to as a linear data structure. Arrays and linked lists are two examples of linear data structures.
- Non-Linear Data Structure: Non-linear data structures are data structures in which data elements are not arranged linearly or sequentially. We cannot walk through all elements in one pass in a non-linear data structure, as in a linear data structure. Trees and graphs are two examples of non-linear data structures.
7. **What is a stack data structure? What are the applications of stack?**

A stack is a data structure that is used to represent the state of an application at a particular point in time. The stack consists of a series of items that are added to the top of the stack and then removed from the top. It is a linear data structure that follows a particular order in which operations are performed. LIFO (Last In First Out) or FILO (First In Last Out) are two possible orders. A stack consists of a sequence of items. The element that's added last will come out first, a real-life example might be a stack of clothes on top of each other. When we remove the cloth that was previously on top, we can say that the cloth that was added last comes out first.

Following are some applications for stack data structure:

- It acts as temporary storage during recursive operations
- Redo and Undo operations in doc editors
- Reversing a string
- Parenthesis matching
- Postfix to Infix Expressions
- Function calls order
8. **What are different operations available in stack data structure?**

Some of the main operations provided in the stack data structure are:

- push: This adds an item to the top of the stack. The overflow condition occurs if the stack is full.
- pop: This removes the top item of the stack. Underflow condition occurs if the stack is empty.
- top: This returns the top item from the stack.
- isEmpty: This returns true if the stack is empty else false.
- size: This returns the size of the stack.
9. **What is a queue data structure? What are the applications of queue?**

   A queue is a linear data structure that allows users to store items in a list in a systematic manner. The items are added to the queue at the rear end until they are full, at which point they are removed from the queue from the front. Queues are commonly used in situations where the users want to hold items for a long period of time, such as during a checkout process. A good example of a queue is any queue of customers for a resource where the first consumer is served first.

   Following are some applications of queue data structure:

- Breadth-first search algorithm in graphs
- Operating system: job scheduling operations, Disk scheduling, CPU scheduling etc.
- Call management in call centres
10. **What are different operations available in queue data structure?**
- enqueue: This adds an element to the rear end of the queue. Overflow conditions occur if the queue is full.
- dequeue: This removes an element from the front end of the queue. Underflow conditions occur if the queue is empty.
- isEmpty: This returns true if the queue is empty or else false.
- rear: This returns the rear end element without removing it.
- front: This returns the front-end element without removing it.
- size: This returns the size of the queue.
11. **Differentiate between stack and queue data structure.**

**Stack Queue![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.003.png)**

Stack is a linear data structure Queue is a linear data structure where data is added and removed where data is ended at the rear end from the top. and removed from the front.

Stack is based on LIFO(Last In Queue is based on FIFO(First In First First Out) principle Out) principle

Insertion operation in Stack is Insertion operation in Queue is known as push. known as eneque.

Delete operation in Stack is Delete operation in Queue is known known as pop. as dequeue.

Only one pointer is available for Two pointers are available for both addition and deletion: top() addition and deletion: front() and

rear()

Used in solving recursion Used in solving sequential processing problems problems

12. **How to implement a queue using stack?**

A queue can be implemented using two stacks. Let q be the queue andstack1 and stack2 be the 2 stacks for implementing q. We know that stack supports push, pop, and peek operations and using these operations, we need to emulate the operations of the queue - enqueue and dequeue. Hence, queue q can be implemented in two methods (Both the methods use auxillary space complexity of O(n)):

1. By making enqueue operation costly:
- Here, the oldest element is always at the top of stack1 which ensures dequeue operation occurs in O(1) time complexity.
- To place the element at top of stack1, stack2 is used.
- Pseudocode:
- Enqueue: Here time complexity will be O(n)

enqueue(q, data):

While stack1 is not empty:

Push everything from stack1 to stack2.

Push data to stack1

Push everything back to stack1.

- Dequeue: Here time complexity will be O(1)

deQueue(q):

If stack1 is empty then error else Pop an item from stack1 and return it

2. By making the dequeue operation costly:
- Here, for enqueue operation, the new element is pushed at the top of stack1. Here, the enqueue operation time complexity is O(1).
- In dequeue, if stack2 is empty, all elements from stack1 are moved to stack2 and top of stack2 is the result. Basically, reversing the list by pushing to a stack and returning the first enqueued element. This operation of pushing all elements to a new stack takes O(n) complexity.
- Pseudocode:
- Enqueue: Time complexity: O(1)

enqueue(q, data): Push data to stack1

- Dequeue: Time complexity: O(n)

dequeue(q):

If both stacks are empty then raise error.

If stack2 is empty:

While stack1 is not empty:

push everything from stack1 to stack2.

Pop the element from stack2 and return it.

**13. How do you implement stack using queues?**

1. A stack can be implemented using two queues. We know that a queue supports enqueue and dequeue operations. Using these operations, we need to develop push, pop operations.
1. Let stack be ‘s’ and queues used to implement be ‘q1’ and ‘q2’. Then, stack ‘s’ can be implemented in two ways:
1. By making push operation costly:
   1. This method ensures that the newly entered element is always at the front of ‘q1’ so that pop operation just dequeues from ‘q1’.
   1. ‘q2’ is used as auxillary queue to put every new element in front of ‘q1’ while ensuring pop happens in O(1) complexity.
   1. Pseudocode:
- Push element to stack s: Here push takes O(n) time complexity.

push(s, data):

Enqueue data to q2

Dequeue elements one by one from q1 and enqueue to q2. Swap the names of q1 and q2

- Pop element from stack s: Takes O(1) time complexity.

pop(s):

dequeue from q1 and return it. 2. By making pop operation costly:

- In push operation, the element is enqueued to q1.
- In pop operation, all the elements from q1 except the last remaining element, are pushed to q2 if it is empty. That last element remaining of q1 is dequeued and returned.
- Pseudocode:
- Push element to stack s: Here push takes O(1) time complexity.

push(s,data): Enqueue data to q1

- Pop element from stack s: Takes O(n) time complexity.

pop(s):

Step1: Dequeue every elements except the last element from q1 and enqueue to q2.

Step2: Dequeue the last item of q1, the dequeued item is stored in result variable.

Step3: Swap the names of q1 and q2 (for getting updated data after dequeue) Step4: Return the result.

14. **What is array data structure? What are the applications of arrays?**

An array data structure is a data structure that is used to store data in a way that is efficient and easy to access. It is similar to a list in that it stores data in a sequence. However, an array data structure differs from a list in that it can hold much more data than a list can. An array data structure is created by combining several arrays together. Each array is then given a unique identifier, and each array’s data is stored in the order in which they are created.

Array data structures are commonly used in databases and other computer systems to store large amounts of data efficiently. They are also useful for storing information that is frequently accessed, such as large amounts of text or images.

15. **Elaborate on different types of array data structure**

There are several different types of arrays:

- One-dimensional array: A one-dimensional array stores its elements in contiguous memory locations, accessing them using a single index value. It is a linear data structure holding all the elements in a sequence.
- Two-dimensional array: A two-dimensional array is a tabular array that includes rows and columns and stores data. An M × N two-dimensional array is created by grouping M rows and N columns into N columns and rows.
- Three-dimensional array: A three-dimensional array is a grid that has rows, columns, and depth as a third dimension. It comprises a cube with rows, columns, and depth as a third dimension. The three-dimensional array has three subscripts for a position in a particular row, column, and depth. Depth (dimension or layer) is the first index, row index is the second index, and column index is the third index.
16. **What is a linked list data structure? What are the applications for the Linked list?**

    A linked list can be thought of as a series of linked nodes (or items) that are connected by links (or paths). Each link represents an entry into the linked list, and each entry points to the next node in the sequence. The order in which nodes are added to the list is determined by the order in which they are created.

    Following are some applications of linked list data structure:

- Stack, Queue, binary trees, and graphs are implemented using linked lists.
- Dynamic management for Operating System memory.
- Round robin scheduling for operating system tasks.
- Forward and backward operation in the browser.
17. **Elaborate on different types of Linked List data structures?**

Following are different types of linked lists:

1. Singly Linked List: A singly linked list is a data structure that is used to store multiple items. The items are linked together using the key. The key is used to identify the item and is usually a unique identifier. In a singly linked list, each item is stored in a separate node. The node can be a single object or it can be a collection of objects. When an item is added to the list, the node is updated and the new item is added to the end of the list. When an item is removed from the list, the node that contains the removed item is deleted and its place is taken by another node. The key of a singly linked list can be any type of data structure that can be used to identify an object. For example, it could be an integer, a string, or even another singly linked list. Singly-linked lists are useful for storing many different types of data. For example, they are commonly used to store lists of items such as grocery lists or patient records. They are also useful for storing data that is time sensitive such as stock market prices or flight schedules.
1. Doubly Linked List: A doubly linked list is a data structure that allows for two-way data access such that each node in the list points to the next node in the list and also points back to its previous node. In a doubly linked list, each node can be accessed by its address, and the contents of the node can be accessed by its index. It's ideal for

   applications that need to access large amounts of data in a fast manner. A disadvantage of a doubly linked list is that it is more difficult to maintain than a single-linked list. In addition, it is more difficult to add and remove nodes than in a single-linked list.

3. Circular Linked List: A circular linked list is a unidirectional linked list where each node points to its next node and the last node points back to the first node, which makes it circular.
3. Doubly Circular Linked List: A doubly circular linked list is a linked list where each node points to its next node and its previous node and the last node points back to the first node and first node’s previous points to the last node.
3. Header List: A list that contains the header node at the beginning of the list, is called the header-linked list. This is helpful in calculating some repetitive operations like the number of elements in the list etc.
18. **Difference between Array and Linked List.**

**Arrays Linked Lists![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.004.png)**

An array is a collection of data A linked list is a collection of entities elements of the same type. known as nodes. The node is divided

into two sections: data and address.

It keeps the data elements in a It stores elements at random, or single memory. anywhere in the memory.

The memory size of an array is The memory size of a linked list is fixed and cannot be changed allocated during runtime.

during runtime.

An array's elements are not Linked List elements are dependent on dependent on one another. one another.

It is easier and faster to access In the linked list, it takes time to access an element in an array. an element.

Memory utilization is ineffective Memory utilization is effective in the in the case of an array. case of linked lists.

Operations like insertion and Operations like insertion and deletion deletion take longer time in an are faster in the linked list.

array.

19. **What is an asymptotic analysis of an algorithm?**

Asymptotic analysis of an algorithm defines the run-time performance as per its mathematical boundations. Asymptotic analysis helps us articulate the best case(Omega Notation, Ω), average case(Theta Notation, θ), and worst case(Big Oh Notation, Ο) performance of an algorithm.

20. **What is hashmap in data structure?**

Hashmap is a data structure that uses an implementation of a hash table data structure which allows access to data in constant time (O(1)) complexity if you have the key.

21. **What is the requirement for an object to be used as key or value in HashMap?**
- The key or value object that gets used in the hashmap must implement equals() and hashcode() method.
- The hash code is used when inserting the key object into the map and the equals method is used when trying to retrieve a value from the map.
22. **How does HashMap handle collisions in Java?**
- The java.util.HashMap class in Java uses the approach of chaining to handle collisions. In chaining, if the new values with the same key are attempted to be pushed, then these values are stored in a linked list stored in a bucket of the key as a chain along with the existing value.
- In the worst-case scenario, it can happen that all keys might have the same hashcode, which will result in the hash table turning into a linked list. In this case, searching a value will take O(n) complexity as opposed to O(1) time due to the nature of the linked list. Hence, care has to be taken while selecting hashing algorithm.
23. **What is the time complexity of basic operations get() and put() in HashMap class?**

    The time complexity is O(1) assuming that the hash function used in the hash map distributes elements uniformly among the buckets.

    **Data Structure Interview Questions for Experienced**

1. **What is binary tree data structure? What are the applications for binary trees?**

   A binary tree is a data structure that is used to organize data in a way that allows for efficient retrieval and manipulation. It is a data structure that uses two nodes, called leaves and nodes, to represent the data. The leaves represent the data and the nodes represent the relationships between the leaves. Each node has two children, called siblings, and each child has one parent. The parent is the node that is closest to the root of the tree. When a node is deleted from the tree, it is deleted from both its child and its parent.

   Following are some applications for binary tree data structure:

- It's widely used in computer networks for storing routing table information.
- Decision Trees.
- Expression Evaluation.
- Database indices.
2. **What is binary search tree data structure? What are the applications for binary search trees?**

   A binary search tree is a data structure that stores items in sorted order. In a binary search tree, each node stores a key and a value. The key is used to access the item and the value is used to determine whether the item is present or not. The key can be any type of value such as an integer, floating point number, character string, or even a combination of these types. The value can be any type of items such as an integer, floating point number, character string, or even a combination of these types. When a node is added to the tree, its key is used to access the item stored at that node. When a node is removed from the tree, its key is used to access the item stored at that node.

   A binary search tree is a special type of binary tree that has a specific order of elements in it. It has three basic qualities:

- All elements in the left subtree of a node should have a value less than or equal to the parent node's value, and
- All elements in the right subtree of a node should have a value greater than or equal to the parent node's value.
- Both the left and right subtrees must be binary search trees too.

Following are some applications for binary tree data structure:

- It is used for indexing and multi-level indexing.
- It is used for implementing various search algorithms.
- It is helpful in organizing a sorted stream of data.
3. **What are tree traversals?**

Tree traversal is the process of visiting all the nodes of a tree. Since the root (head) is the first node and all nodes are connected via edges (or links) we always start with that node. There are three ways which we use to traverse a tree −

1\. Inorder Traversal:

- Algorithm:
  - Step 1. Traverse the left subtree, i.e., call Inorder(root.left)
  - Step 2. Visit the root.
  - Step 3. Traverse the right subtree, i.e., call Inorder(root.right)
- Inorder traversal in Java:

// Print inorder traversal of given tree.

void printInorderTraversal(Node root) {![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.005.png)

if (root == null)

return;

//first traverse to the left subtree printInorderTraversal(root.left); //then print the data of node System.out.print(root.data + " "); //then traverse to the right subtree printInorderTraversal(root.right);

}![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.006.png)

1. Uses: In binary search trees (BST), inorder traversal gives nodes in ascending order.
2. Preorder Traversal:
   1. Algorithm:
      1. Step 1. Visit the root.
      1. Step 2. Traverse the left subtree, i.e., call Preorder(root.left)
      1. Step 3. Traverse the right subtree, i.e., call Preorder(root.right)
   1. Preorder traversal in Java:

// Print preorder traversal of given tree.

void printPreorderTraversal(Node root) {![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.007.png)

if (root == null)

return;

//first print the data of node System.out.print(root.data + " "); //then traverse to the left subtree printPreorderTraversal(root.left); //then traverse to the right subtree printPreorderTraversal(root.right);

}![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.008.png)

- Uses:
- Preorder traversal is commonly used to create a copy of the tree.
- It is also used to get prefix expression of an expression tree.
3. Postorder Traversal:
- Algorithm:
  - Step 1. Traverse the left subtree, i.e., call Postorder(root.left)
  - Step 2. Traverse the right subtree, i.e., call Postorder(root.right)
  - Step 3. Visit the root.
- Postorder traversal in Java:

// Print postorder traversal of given tree. void printPostorderTraversal(Node root) {

if (root == null)

return;![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.009.png)

//first traverse to the left subtree printPostorderTraversal(root.left); //then traverse to the right subtree printPostorderTraversal(root.right); //then print the data of node System.out.print(root.data + " ");

}

- Uses:
- Postorder traversal is commonly used to delete the tree.
- It is also useful to get the postfix expression of an expression tree.

Consider the following tree as an example, then:

- Inorder Traversal => Left, Root, Right : [4, 2, 5, 1, 3]
- Preorder Traversal => Root, Left, Right : [1, 2, 4, 5, 3]
- Postorder Traversal => Left, Right, Root : [4, 5, 2, 3, 1]
4. **What is a deque data structure and its types? What are the applications for deque?**

   A deque can be thought of as an array of items, but with one important difference: Instead of pushing and popping items off the end to make room, deques are designed to allow items to be inserted at either end. This property makes deques well-suited for performing tasks such as keeping track of inventory, scheduling tasks, or handling large amounts of data.

   There are two types of deque:

- Input Restricted Deque: Insertion operations are performed at only one end while deletion is performed at both ends in the input restricted queue.
- Output Restricted Deque: Deletion operations are performed at only one end while insertion is performed at both ends in the output restricted queue.

Following are some real-time applications for deque data structure:

- It can be used as both stack and queue, as it supports all the operations for both data structures.
- Web browser’s history can be stored in a deque.
- Operating systems job scheduling algorithm.
5. **What are some key operations performed on the Deque data structure?**

   Following are the key operations available deque:

- *insertFront()*: This adds an element to the front of the Deque.
- *insertLast()*: This adds an element to the rear of the Deque.
- *deleteFront()*: This deletes an element from the front of the Deque.
- *deleteLast()*:This deletes an element from the front of the Deque.
- *getFront()*: This gets an element from the front of the Deque.
- *getRear()*: This gets an element from the rear of the Deque.
- *isEmpty()*: This checks whether Deque is empty or not.
- *isFull()*: This checks whether Deque is full or not.
6. **What is a priority queue? What are the applications for priority queue?**

   Priority Queue is an abstract data type that is similar to a queue in that each element is assigned a priority value. The order in which elements in a priority queue are served is determined by their priority (i.e., the order in which they are removed). If the elements have the same priority, they are served in the order they appear in the queue.

   Following are some real-time applications for priority queue:

- Used in graph algorithms like Dijkstra, Prim’s Minimum spanning tree etc.
- Huffman code for data compression
- Finding Kth Largest/Smallest element
7. **Compare different implementations of priority queue**

The following table contains an asymptotic analysis of different implementations of a priority queue:

**Operations peek insert delete![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.010.png)**

**Linked List** O(1) O(n) O(1)![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.011.png)

**Binary Heap** O(1) O(log n) O(log n)

**Binary Search Tree** O(1) O(log n) O(log n)

8. **What is graph data structure and its representations? What are the applications for graphs?**

   A graph is a type of non-linear data structure made up of nodes and edges. The nodes are also known as vertices, and edges are lines or arcs that connect any two nodes in the graph.

   The following are the two most common graph representations:

1. Adjacency Matrix: Adjacency Matrix is a two-dimensional array with the dimensions V x V, where V is the number of vertices in a graph. Representation is simpler to implement and adhere to. It takes O(1) time to remove an edge. Queries such as whether there is an edge from vertex 'u' to vertex 'v' are efficient and can be completed in O(1).

   One of the cons of this representation is that even if the graph is sparse (has fewer edges), it takes up the same amount of space. Adding a vertex takes O(V^2). It also takes O(V) time to compute all of a vertex's neighbours, which is not very efficient.

2. Adjacency List: In this method, each Node holds a list of Nodes that are directly connected to that vertex. Each node at the end of the list is connected with null values to indicate that it is the last node in the list. This saves space O(|V|+|E|). In the worst-case scenario, a graph can have C(V, 2) edges, consuming O(V^2) space. It is simpler to add a vertex. It takes the least amount of time to compute all of a vertex's neighbours.

   One of the cons of this representation is that queries such as "is there an edge from vertex u to vertex v?" are inefficient and take O (V) in the worst case.

9. **What is the difference between the Breadth First Search (BFS) and Depth First Search (DFS)?**

**Breadth First Search (BFS) Depth First Search (DFS)![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.012.png)**

It stands for “Breadth First Search” It stands for “Depth First Search”

BFS (Breadth First Search) finds the DFS (Depth First Search) finds the shortest path using the Queue data shortest path using the Stack data structure. structure.

We walk through all nodes on the same level before passing to the next level in BFS.

DFS begins at the root node and proceeds as far as possible through the nodes until we reach the node with no unvisited nearby nodes.

When compared to DFS, BFS is slower. When compared to BFS, DFS is faster.

BFS performs better when the target is DFS performs better when the target is close to the source. far from the source.

BFS necessitates more memory. DFS necessitates less memory.

Nodes that have been traversed multiple When there are no more nodes to visit, times are removed from the queue. the visited nodes are added to the stack

and then removed.

Backtracking is not an option in BFS. The DFS algorithm is a recursive

algorithm that employs the concept of backtracking.

It is based on the FIFO principle (First In It is based on the LIFO principle (Last In First Out). First Out).

10. **What is AVL tree data structure, its operations, and its rotations? What are the applications for AVL trees?**

    AVL trees are height balancing binary search trees named after their inventors Adelson, Velski, and Landis. The AVL tree compares the heights of the left and right subtrees and ensures that the difference is less than one. This distinction is known as the Balance Factor.

    BalanceFactor = height(left-subtree) − height(right-subtree) We can perform the following two operations on AVL tree:

- Insertion: Insertion in an AVL tree is done in the same way that it is done in a binary search tree. However, it may cause a violation in the AVL tree property, requiring the tree to be balanced. Rotations can be used to balance the tree.
- Deletion: Deletion can also be performed in the same manner as in a binary search tree. Because deletion can disrupt the tree's balance, various types of rotations are used to rebalance it.

An AVL tree can balance itself by performing the four rotations listed below:

- Left rotation: When a node is inserted into the right subtree of the right subtree and the tree becomes unbalanced, we perform a single left rotation.
- Right rotation: If a node is inserted in the left subtree of the left subtree, the AVL tree may become unbalanced. The tree then requires right rotation.
- Left-Right rotation: The RR rotation is performed first on the subtree, followed by the LL rotation on the entire tree.
- Right-Left rotation: The LL rotation is performed first on the subtree, followed by the RR rotation on the entire tree.

Following are some real-time applications for AVL tree data structure:

- AVL trees are typically used for in-memory sets and dictionaries.
- AVL trees are also widely used in database applications where there are fewer insertions and deletions but frequent data lookups are required.
- Apart from database applications, it is used in applications that require improved searching.
11. **What is a B-tree data structure? What are the applications for B-trees?**

    The B Tree is a type of m-way tree that is commonly used for disc access. A B-Tree with order m can only have m-1 keys and m children. One of the primary reasons for using a B tree is its ability to store a large number of keys in a single node as well as large key values while keeping the tree's height relatively small.

    A B-tree of order 4 is shown below in the image: Following are the key properties of a B-tree data structure:

- All of the leaves are at the same height.
- The term minimum degree 't' describes a B-Tree. The value of t is determined by the size of the disc block.
- Except for root, every node must have at least t-1 keys. The root must contain at least one key.
- All nodes (including root) can have no more than 2\*t - 1 keys.
- The number of children of a node is equal to its key count plus one.
- A node's keys are sorted in ascending order. The child of two keys k1 and k2 contains all keys between k1 and k2.
- In contrast to Binary Search Tree, B-Tree grows and shrinks from the root.

Following are real-time applications of a B-Tree data structure:

- It is used to access data stored on discs in large databases.
- Using a B tree, you can search for data in a data set in significantly less time.
- The indexing feature allows for multilevel indexing.
- The B-tree approach is also used by the majority of servers.
12. **Define Segment Tree data structure and its applications.**

A segment Tree is a binary tree that is used to store intervals or segments. The Segment Tree is made up of nodes that represent intervals. Segment Tree is used when there are multiple range queries on an array and changes to array elements.

The segment tree of array A[7] will look like this:

Following are key operations performed on the Segment tree data structure:

- Building Tree: In this step, we create the structure and initialize the segment tree variable.
- Updating the Tree: In this step, we change the tree by updating the array value at a point or over an interval.
- Querying Tree: This operation can be used to run a range query on the array.

Following are real-time applications for Segment Tree:

- Used to efficiently list all pairs of intersecting rectangles from a list of rectangles in the plane.
- The segment tree has become popular for use in pattern recognition and image processing.
- Finding range sum/product, range max/min, prefix sum/product, etc
- Computational geometry
- Geographic information systems
- Static and Dynamic RMQ (Range Minimum Query)
- Storing segments in an arbitrary manner
13. **Define Trie data structure and its applications**

The word "Trie" is an abbreviation for "retrieval." Trie is a data structure that stores a set of strings as a sorted tree. Each node has the same number of pointers as the number of alphabet characters. It can look up a word in the dictionary by using its prefix. Assuming that all strings are formed from the letters 'a' to 'z' in the English alphabet, each trie node can have a maximum of 26 points.

Trie is also referred to as the digital tree or the prefix tree. The key to which a node is connected is determined by its position in the Trie. Trie allows us to insert and find strings in O(L) time, where L is the length of a single word. This is clearly faster than BST. Because of how it is implemented, this is also faster than Hashing. There is no need to compute a hash function. There is no need to handle collisions (like we do in open addressing and separate chaining)

Another benefit of Trie is that we can easily print all words in alphabetical order, which is not easy with hashing. Trie can also perform prefix search (or auto-complete) efficiently.

The main disadvantage of tries is that they require a large amount of memory to store the strings. We have an excessive number of node pointers for each node

Following are some real-time applications for Trie data structure:

- Auto-Complete and Search for Search Engines
- Genome Analysis
- Data Analytics
- Browser History
- Spell Checker
14. **Define Red-Black Tree and its applications**

Red Black Trees are a type of self-balancing binary search tree. Rudolf Bayer invented it in 1972 and dubbed it "symmetric binary B-trees."

A red-black tree is a Binary tree in which each node has a colour attribute, either red or black. By comparing the node colours on any simple path from the root to a leaf, red-black trees ensure that no path is more than twice as long as any other, ensuring that the tree is generally balanced.

Red-black trees are similar to binary trees in that they both store their data in two's complementary binary formats. However, red-black trees have one important advantage over binary trees: they are faster to access. Because red-black trees are so fast to access, they are often used to store large amounts of data.

Red-black trees can be used to store any type of data that can be represented as a set of values.

Every Red-Black Tree Obeys the Following Rules:

- Every node is either red or black.
- The tree's root is always black.
- There are no two red nodes that are adjacent.
- There is the same number of black nodes on every path from a node to any of its descendant's NULL nodes.
- All of the leaf nodes are black.

Following are some real-time applications for the Red-Black Tree data structure:

- The majority of self-balancing BST library functions in C++ or Java use Red-Black Trees.
- It is used to implement Linux CPU Scheduling.
- It is also used to reduce time complexity in the K-mean clustering algorithm in machine learning.
- MySQL also employs the Red-Black tree for table indexes in order to reduce searching and insertion time.
15. **Which data structures are used for implementing LRU cache?**

LRU cache or Least Recently Used cache allows quick identification of an element that hasn’t been put to use for the longest time by organizing items in order of use. In order to achieve this, two data structures are used:

- Queue – This is implemented using a doubly-linked list. The maximum size of the queue is determined by the cache size, i.e by the total number of available frames. The least recently used pages will be near the front end of the queue whereas the most recently used pages will be towards the rear end of the queue.
- Hashmap – Hashmap stores the page number as the key along with the address of the corresponding queue node as the value.
16. **What is a heap data structure?**

Heap is a special tree-based non-linear data structure in which the tree is a complete binary tree. A binary tree is said to be complete if all levels are completely filled except possibly the last level and the last level has all elements as left as possible. Heaps are of two types:

- Max-Heap:
  - In a Max-Heap the data element present at the root node must be the greatest among all the data elements present in the tree.
  - This property should be recursively true for all sub-trees of that binary tree.
- Min-Heap:
- In a Min-Heap the data element present at the root node must be the smallest (or minimum) among all the data elements present in the tree.
- This property should be recursively true for all sub-trees of that binary tree.

**What is an Algorithm?**

Algorithms and Data Structures are a crucial component of any technical [coding interview](https://www.interviewbit.com/coding-interview-questions/). It does not matter if you are a C++ programmer, a Java programmer, or a Web developer using JavaScript, Angular, React, JQuery, or any other programming language.

A programmer should have a thorough understanding of both basic data structures, such as arrays, linked lists, trees, hash tables, stacks, and queues, etc. and conventional algorithms, such as Binary Search, Dynamic Programming, and so on. Therefore, in this article we would be mostly focussing on Algorithms - an introduction to algorithms, a lot of algorithms interview questions which are being asked in the coding interviews of various companies and also a few Algorithms MCQs which we think everyone should practice in order to have a better understanding of algorithms.

Now, the very first question which must be popping in your head must be "What is an algorithm?" Well, the answer to this question is: An algorithm is a finite sequence of well-defined instructions used to solve a class of problems or conduct a computation in mathematics and computer science.

Algorithms are used to specify how calculations, data processing, automated reasoning, automated decision making, and other tasks should be done. An algorithm is a method for calculating a function that can be represented in a finite amount of space and time and in a well defined formal language. The instructions describe a computation that, when run, continues through a finite number of well defined subsequent stages, finally creating "output" and terminating at a final ending state, starting from an initial state and initial input (possibly empty). The shift from one state to the next is not always predictable; some algorithms, known as randomised algorithms, take random input into account.

**The Need For Algorithms (Advantages of Algorithms):**

Before diving deep into algorithm interview questions, let us first understand the need for Algorithms in today's world. The following are some of the benefits of using algorithms in real-world problems.

- Algorithms boost the effectiveness of an existing method.
- It is easy to compare an algorithm's performance to those of other approaches using various methods (Time Complexity, Space Complexity, etc.).
- Algorithms provide the designers with a detailed description of the criteria and goals of the problems.
- They also enable a reasonable comprehension of the program's flow.
- Algorithms evaluate how well the approaches work in various scenarios (Best cases, worst cases, average cases).
- An algorithm also determines which resources (input/output, memory) cycles are necessary.
- We can quantify and assess the problem's complexity in terms of time and space using an algorithm.
- The cost of design is also reduced if proper algorithms are used.

**Algorithm Interview Questions for Freshers**

1. **How can we compare between two algorithms written for the same problem?**

   The complexity of an algorithm is a technique that is used to categorise how efficient it is in comparison to other algorithms. It focuses on how the size of the data set to be processed affects execution time. In computing, the algorithm's computational complexity is critical. It is a good idea to categorise algorithms according to how much time or space they take up and to describe how much time or space they take up as a function of input size.

- Complexity of Time: The running time of a program as a function of the size of the input is known as time complexity.
- Complexity of Space: Space complexity examines algorithms based on how much space they require to fulfil their tasks. In the early days of computers, space complexity analysis was crucial (when storage space on the computer was limited).

Note: Nowadays, a lack of space is rarely an issue because computer storage is plentiful. Therefore, it is mostly the Time Complexity that is given more importance while evaluating an Algorithm.

2. **What do you understand by the best case, worst case and average case scenario of an algorithm?**

   The mathematical foundation/framing of an algorithm's run time performance is defined by asymptotic analysis. We can easily determine the best case, average case, and worst-case scenarios of an algorithm using asymptotic analysis.

- Best Case Scenario of an Algorithm: The best-case scenario for an algorithm is defined as the data arrangement in which the algorithm performs the best. Take a binary search, for example, where the best-case scenario is if the target value is in the very centre of the data we are looking for. The best-case scenario for binary search would have a time complexity of O(1) or constant time complexity.
- Worst Case Scenario of an Algorithm: The worst collection of input for a given algorithm is referred to as the worst-case scenario of an Algorithm. For example, quicksort can perform poorly if the pivot value is set to the largest or smallest element of a sublist. Quicksort will degenerate into an algorithm with a time complexity of O(n^2), where n is the size of the list to be sorted.
- Average Case Scenario of an Algorithm: The average-case complexity of an algorithm is the amount of some computational resource (usually time) used by the process, averaged over all possible inputs, according to computational complexity theory. For example, the average-case complexity of the randomised quicksort algorithm is O(n\*log(n)), where n is the size of the list to be sorted.
3. **What do you understand by the Asymptotic Notations?**

Asymptotic analysis is a technique that is used for determining the efficiency of an algorithm that does not rely on machine-specific constants and avoids the algorithm from comparing itself to the time-consuming approach. For asymptotic analysis, asymptotic notation is a mathematical technique that is used to indicate the temporal complexity of algorithms.

The following are the three most common asymptotic notations.

- Big Theta Notation: (θ Notation)

  The exact asymptotic behaviour is defined using the theta (θ) Notation. It binds

  functions from above and below to define behaviour. Dropping low order terms and ignoring leading constants is a convenient approach to get Theta notation for an expression.

- Big O Notation:

  The Big O notation defines an upper bound for an algorithm by bounding a function from above. Consider the situation of insertion sort: in the best case scenario, it takes linear time, and in the worst case, it takes quadratic time. Insertion sort has a time complexity O(n^2). It is useful when we just have an upper constraint on an algorithm's time complexity.

- Big Omega (Ω) Notation:

  The Ω Notation provides an asymptotic lower bound on a function, just like Big O notation does. It is useful when we have a lower bound on an algorithm's time complexity.![ref1]

4. **Write an algorithm to swap two given numbers in Java without using a temporary variable.**

   It is a trick question that is frequently asked in the interviews of various companies. This problem can be solved in a variety of ways. However, while solving the problem, we must solve it without using a temporary variable, which is an essential condition. For this problem, if we can consider the possibility of integer overflow in our solution while coming up with an approach to solving it, we can make a great impression on interviewers.

   Let us say that we have two integers a and b, with a's value equal to 5 and b's value equal to 6, and we want to swap them without needing a third variable. We will need to use Java programming constructs to solve this problem. Mathematical procedures such as addition, subtraction, multiplication, and division can be used to swap numbers. However, it is possible that it will cause an integer overflow problem.

   Let us take a look at two approaches to solve this problem: Using Addition and subtraction:

   a = a + b;

   b = a - b; // this will act like (a+b) - b, and now b equals a. a = a - b; // this will act like (a+b) - a, and now an equals b.

   It is a clever trick. However, if the addition exceeds the maximum value of the int primitive type as defined by Integer.MAX\_VALUE in Java, or if the subtraction is less than the minimum value of the int primitive type as defined by Integer.MIN\_VALUE in Java, there will be an integer overflow.

   Using the XOR method:

   Another way to swap two integers without needing a third variable (temporary variable) is using the XOR method. This is often regarded as the best approach because it works in languages that do not handle integer overflows, such as Java, C, and C++. Java has a number of bitwise operators. XOR (denoted by ^) is one of them.

   x = x ^ y; y = x ^ y; x = x ^ y;

5. **Explain the Divide and Conquer Algorithmic Paradigm. Also list a few algorithms which use this paradigm.**

   Divide and Conquer is an algorithm paradigm, not an algorithm itself. It is set up in such a way that it can handle a large amount of data, split it down into smaller chunks, and determine the solution to the problem for each of the smaller chunks. It combines all of the piecewise solutions of the smaller chunks to form a single global solution. This is known as the divide and conquer technique. The Divide and Conquer algorithmic paradigm employ the steps given below:

- Divide: The algorithm separates the original problem into a set of subproblems in this step.
- Conquer: The algorithm solves each subproblem individually in this step.
- Combine: In this step, the algorithm combines the solutions to the subproblems to obtain the overall solution.

Some of the algorithms which use the Divide and Conquer Algorithmic paradigm are as follows:

- Binary Search
- Merge Sort
- Strassen's Matrix Multiplication
- Quick Sort
- Closest pair of points.
6. **What do you understand about greedy algorithms? List a few examples of greedy algorithms.**

   A greedy algorithm is an algorithmic method that aims to choose the best optimal decision at each sub-step, eventually leading to a globally optimal solution. This means that the algorithm chooses the best answer available at the time, regardless of the consequences. In other words, when looking for an answer, an algorithm always selects the best immediate, or local, option. Greedy algorithms may identify less than perfect answers for some cases of other problems while finding the overall, ideal solution for some idealistic problems.

   The Greedy algorithm is used in the following algorithms to find their solutions:

- Prim's Minimal Spanning Tree Algorithm
- Kruskal's Minimal Spanning Tree Algorithm
- Travelling Salesman Problem
- Fractional Knapsack Problem
- Dijkstra's Algorithm
- Job Scheduling Problem
- Graph Map Coloring
- Graph Vertex Cover.
7. **What do you understand by a searching algorithm? List a few types of searching algorithms.**

   Searching Algorithms are used to look for an element or get it from a data structure (usually a list of elements). These algorithms are divided into two categories based on the type of search operation:

- Sequential Search: This method traverses the list of elements consecutively, checking each element and reporting if the element to be searched is found. Linear Search is an example of a Sequential Search Algorithm.
- Interval Search: These algorithms were created specifically for searching sorted data structures. Because they continually target the centre of the search structure and divide the search space in half, these types of search algorithms are far more efficient than Sequential Search algorithms. Binary Search is an example of an Interval Search Algorithm.
8. **Describe the Linear Search Algorithm.**

To find an element in a group of elements, the linear search can be used. It works by traversing the list of elements from the beginning to the end and inspecting the properties of all the elements encountered along the way. Let us consider the case of an array containing some integer elements. We want to find out and print all of the elements' positions that match a particular value (also known as the "key" for the linear search). The linear search works in a flow here, matching each element with the number from the beginning to the end of the list, and then printing the element's location if the element at that position is equal to the key.

Given below is an algorithm describing Linear Search:

- Step 1: Using a loop, traverse the list of elements given.
- Step 2: In each iteration, compare the target value (or key-value) to the list's current value.
- Step 3: If the values match, print the array's current index.
- Step 4: Move on to the next array element if the values do not match.
- Step 5: Repeat Steps 1 to 4 till the end of the list of elements is reached.

The time complexity of the Linear Search Algorithm is O(n) where n is the size of the list of elements and its space complexity is constant, that is, O(1).

9. **Describe the Binary Search Algorithm.**

To apply binary search on a list of elements, the prerequisite is that the list of elements should be sorted. It is based on the Divide and Conquers Algorithmic paradigm. In the Binary Search Algorithm, we divide the search interval in half periodically to search the sorted list. We begin by creating an interval that spans the entire list. If the search key's value is less than the item in the interval's midpoint, the interval should be narrowed to the lower half. Otherwise, we limit it to the upper half of the page. We check for the value until it is discovered or the interval is empty. Given below is an algorithm describing Binary Search: (Let us assume that the element to be searched is x and the array of elements is sorted in ascending order)

- Step 1: x should be firstly compared to the middle element.
- Step 2: We return the middle element's index if x matches the middle element.
- Step 3: Else If x is greater than the middle element, x can only be found after the middle element in the right half subarray since the array is sorted in the ascending order. As a result, we repeat the process for the right half.
- Step 4: Otherwise, we repeat for the left half (x is smaller).
- Step 5: If the interval is empty, we terminate the binary search.

The time complexity of the Binary Search Algorithm is O(log(n)) where n is the size of the list of elements and its space complexity is constant, that is, O(1).

10. **Write down an algorithm for adding a node to a linked list sorted in ascending order(maintaining the sorting property).**

    An algorithm for adding a node to a link list sorted in ascending order (maintaining the sorting property) is given below:

- Step 1: Check if the linked list has no value (or is empty). If yes, then set the new node as the head and return it.
- Step 2: Check if the value of the node to be inserted is smaller than the value of the head node. If yes, place it at the beginning and make it the head node.
- Step 3: Find the suitable node after which the input node should be added in a loop. To discover the required node, begin at the head and work your way forward until you reach a node whose value exceeds the input node. The preceding node is the correct node.
- Step 4: After the correct node is found in step 3, insert the node.
11. **Write an algorithm for counting the number of leaf nodes in a binary tree.**

    An algorithm for counting the number of leaf nodes in a binary tree is given below:

- Step 1: If the current node is null, return a value 0.
- Step 2: If a leaf node is encountered, that is, if the current node's left and right nodes are both null, then return 1.
- Step 3: Calculate the number of leaf nodes recursively by adding the number of leaf nodes in the left subtree by the number of leaf nodes in the right subtree.
12. **What do you understand about the Dynamic Programming (DP) Algorithmic Paradigm? List a few problems which can be solved using the same.**

    Dynamic Programming is primarily a recursion optimization. We can use Dynamic Programming to optimise any recursive solution that involves repeated calls for the same inputs. The goal is to simply save the results of subproblems so that we do not have to recalculate them later. The time complexity of this simple optimization is reduced from exponential to polynomial. For example, if we create a simple recursive solution for Fibonacci Numbers, the time complexity is exponential, but if we optimise it by storing subproblem answers using Dynamic Programming, the time complexity is linear.

    The following codes illustrate the same:

    With Recursion (no DP): The time complexity of the given code will be exponential.

    /\*Sample C++ code for finding nth fibonacci number without DP\*/ **int nFibonacci**(**int** n){

**if**(n == 0 || n == 1) **return** n;

**else return** nFibonacci(n - 1) + nFibonacci(n - 2);

}

With DP: The time complexity of the given code will be linear because of Dynamic Programming.

/\*Sample C++ code for finding nth fibonacci number with DP\*/ **int nFibonacci**(**int** n){

vector<**int**> **fib**(n + 1);

fib[0] = 0;

fib[1] = 1;

**for**(**int** i = 2;i <= n;i ++){

fib[i] = fib[i - 1] + fib[i - 2]; }![](Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.013.png)

**return** fib[n];

}

A few problems which can be solved using the Dynamic Programming (DP) Algorithmic Paradigm are as follows:

- Finding the nth Fibonacci number
- Finding the Longest Common Subsequence between two strings.
- Finding the Longest Palindromic Substring in a string.
- The discrete (or 0-1) Knapsack Problem.
- Shortest Path between any two nodes in a graph (Floyd Warshall Algorithm)
13. **Write down a string reversal algorithm. If the given string is "kitiR," for example, the output should be "Ritik".**

    An algorithm for string reversal is as follows:

- Step 1: Start.
- Step 2: We take two variables l and r.
- Step 3: We set the values of l as 0 and r as (length of the string - 1).
- Step 4: We interchange the values of the characters at positions l and r in the string.
- Step 5: We increment the value of l by one.
- Step 6: We decrement the value of r by one.
- Step 7: If the value of r is greater than the value of l, we go to step 4
- Step 8: Stop.
14. **What do you understand about the BFS (Breadth First Search) algorithm.**

    BFS or Breadth-First Search is a graph traversal technique. It begins by traversing the graph from the root node and explores all of the nodes in the immediate vicinity. It chooses the closest node and then visits all of the nodes that have yet to be visited. Until it reaches the objective node, the algorithm repeats the same method for each of the closest nodes.

    The BFS Algorithm is given below:

- Step 1: Set status = 1 as the first step for all the nodes(ready state).
- Step 2: Set the status of the initial node A to 2, that is, waiting state.
- Step 3: Repeat steps 4 and 5 until the queue is not empty.
- Step 4: Dequeue and process node N from the queue, setting its status to 3, that is, the processed state.
- Step 5: Put all of N's neighbours in the ready state (status = 1) in the queue and set their status to 2 (waiting state)
- Step 6: Exit.
15. **What do you understand about the DFS (Depth First Search) algorithm.**

    Depth First Search or DFS is a technique for traversing or exploring data structures such as trees and graphs. The algorithm starts at the root node (in the case of a graph, any random node can be used as the root node) and examines each branch as far as feasible before retracing. So the basic idea is to start at the root or any arbitrary node and mark it, then advance to the next unmarked node and repeat until there are no more unmarked nodes. After that, go back and check for any more unmarked nodes to cross. Finally, print the path's nodes. The DFS algorithm is given below:

- Step1: Create a recursive function that takes the node's index and a visited array as input.
- Step 2: Make the current node a visited node and print it.
- Step 3: Call the recursive function with the index of the adjacent node after traversing all nearby and unmarked nodes.

**Algorithm Interview Questions for Experienced**

1. **How do the encryption algorithms work?**

e process of transforming plaintext into a secret code format known as "Ciphertext'' is known as encryption. For calculations, this technique uses a string of bits known as "keys" to convert the text. The larger the key, the more potential patterns for producing ciphertext there are. The majority of encryption algorithms use fixed blocks of input with lengths ranging from 64 to 128 bits, while others use the stream technique.

2. **What are few of the most widely used cryptographic algorithms?**

A few of the most widely used cryptographic algorithms are as follows:

- IDEA
- CAST
- CMEA
- 3-way
- Blowfish
- GOST
- LOKI
- DES and Triple DES.
3. **Describe the merge sort algorithm.**

Merge sort (also known as mergesort) is a general-purpose, comparison-based sorting algorithm developed in computer science. The majority of its implementations result in a stable sort, which indicates that the order of equal elements in the input and output is the same. In 1945, John von Neumann devised the merge sort method, which is a divide and conquer algorithm. The following is how a merge sort works conceptually:

- Separate the unsorted list into n sublists, each with one element (a list of one element is considered sorted).
- Merge sublists repeatedly to create new sorted sublists until only one sublist remains. The sorted list will be displayed then.

The time complexity of the Merge Sort Algorithm is O(nlog(n)) where n is the size of the list of the elements to be sorted while the space complexity of the Merge Sort Algorithm is O(n), that is, linear space complexity.

4. **Describe the quick sort algorithm.**

Quicksort is a sorting algorithm that is in place (in-place algorithm is an algorithm that transforms input using no auxiliary data structure). It was created by the British computer scientist Tony Hoare in 1959 and was published in 1961, and it is still a popular sorting algorithm. It can be somewhat quicker than merge sort and two or three times faster than heapsort when properly done.

Quicksort is based on the divide and conquer algorithmic paradigm. It operates by picking a 'pivot' element from the array and separating the other elements into two subarrays based on whether they are greater or less than the pivot. As a result, it is also known as partition exchange sort. The subarrays are then recursively sorted. This can be done in place, with only a little amount of additional RAM (Random Access Memory) required for sorting.

Quicksort is a comparison sorting algorithm, which means it can sort objects of any type that have a "less-than" relation (technically, a total order) declared for them. Quicksort is not a stable sort, which means that the relative order of equal sort items is not retained in efficient implementations. Quicksort (like the partition method) must be written in such a way that it can be called for a range within a bigger array, even if the end purpose is to sort the entire array, due to its recursive nature.

The following are the steps for in-place quicksort:

- If there are less than two elements in the range, return immediately because there is nothing else to do. A special-purpose sorting algorithm may be used for other very small lengths, and the rest of these stages may be avoided.
- Otherwise, choose a pivot value, which is a value that occurs in the range (the precise manner of choice depends on the partition routine, and can involve randomness).
- Partition the range by reordering its elements while determining a point of division so that all elements with values less than the pivot appear before the division and all elements with values greater than the pivot appear after it; elements with values equal to the pivot can appear in either direction. Most partition procedures ensure that the value that ends up at the point of division is equal to the pivot, and is now in its ultimate location because at least one instance of the pivot is present (but termination of quicksort does not depend on this, as long as sub-ranges strictly smaller than the original are produced).
- Apply the quicksort recursively to the sub-range up to the point of division and the sub-range after it, optionally removing the element equal to the pivot at the point of division from both ranges. (If the partition creates a potentially bigger sub-range near the boundary with all elements known to be equal to the pivot, these can also be omitted.)

Quicksort's mathematical analysis reveals that, on average, it takes O(nlog (n) time complexity to sort n items. In the worst-case scenario, it performs in time complexity of O(n^2).

Note: The algorithm's performance can be influenced by the partition routine (including the pivot selection) and other details not fully defined above, possibly to a large extent for specific input arrays. It is therefore crucial to define these alternatives before discussing quicksort's efficiency.

5. **Describe the bubble sort algorithm with the help of an example.**

Bubble sort, also known as sinking sort, is a basic sorting algorithm that iterates through a list, comparing neighbouring elements and swapping them if they are out of order. The list is sent through again and again until it is sorted. The comparison sort method is named from the manner that smaller or larger components "bubble" to the top of the list. This simplistic method performs badly in real-world situations and is mostly used as a teaching aid. Let us take an example to understand how bubble sort works:

Let us assume that the array to be sorted is (50 10 40 20 80). The various passes or rounds of bubble sort are given below:

- First Pass:
  - (50 10 40 20 80) –> ( 10 50 40 20 80 ), Since 50 > 10, the algorithm compares the first two elements and swaps them.
  - ( 10 50 40 20 80 ) –> ( 10 40 50 20 80 ), Since 50 > 40, the algorithm swaps the values at the second and third positions.
  - (10 40 50 20 80) –> (10 40 20 50 80), Since 50 > 3, the algorithm swaps the third and fourth elements.
  - (10 40 20 50 80) -> ( 10 40 20 50 80 ), The method does not swap the fourth and fifth elements because they are already in order (80 > 50).
- Second Pass:
- ( 10 40 20 50 80 ) –> ( 10 40 20 50 80 ) , Elements at first and second position are in order so now swapping.
- ( 10 40 20 50 80 ) –> ( 10 20 40 50 80 ), Since 40 > 20, the algorithm swaps the values at the second and third positions.
- ( 10 20 40 50 80 ) –> ( 10 20 40 50 80 ), Elements at the third and fourth position are in order so now swapping.
- ( 10 20 40 50 80 ) –> ( 10 20 40 50 80 ), Elements at fourth and fifth position are in order so now swapping.

The array is now sorted, but our algorithm is unsure whether it is complete. To know if the algorithm is sorted, it must complete one complete pass without any swaps.

- Third Pass:
- ( 10 20 40 50 80 ) –> ( 10 20 40 50 80 ), Elements at the first and second position are in order so now swapping.
- ( 10 20 40 50 80 ) –> ( 10 20 40 50 80 ), Elements at the second and third position are in order so now swapping.
- ( 10 20 40 50 80 ) –> ( 10 20 40 50 80 ), Elements at the third and fourth position are in order so now swapping.
- ( 10 20 40 50 80 ) –> ( 10 20 40 5 80 ), Elements at the fourth and fifth position are in order so now swapping.
6. **Write an algorithm to find the maximum subarray sum for a given array. In other words, find the maximum sum that can be achieved by taking contiguous elements from a given array of integers.**

   Kadane's algorithm can be used to find the maximum subarray sum for a given array. From left to right, Kadane's algorithm searches the provided array. It then computes the subarray with the largest sum ending at position j in the jth step, and this sum is stored in the variable "currentSum". Furthermore, it computes the subarray with the biggest sum anywhere in the subarray starting from the first position to the jth position, that is, in A[1...j], and stores it in the variable "bestSum". This is done by taking the maximum value of the variable "currentSum" till now and then storing it in the variable "bestSum". In the end, the value of "bestSum" is returned as the final answer to our problem.

   Formally, Kadane's algorithm can be stated as follows:

- Step 1: Initialize the following variables:
  - bestSum = INT\_MIN
  - currentSum = 0 // for empty subarray, it is initialized as value 0
- Step 2: Loop for each element of the array A
- (a) currentSum = currentSum + A[i]
- (b) if(bestSum < currentSum)

bestSum = currentSum

- (c) if(currentSum < 0) currentSum = 0
- Step 3: return bestSum
7. **Explain the Dijkstra's Algorithm to find the shortest path between a given node in a graph to any other node in the graph.**

   Dijkstra's algorithm is a method for determining the shortest pathways between nodes in a graph, which might be used to depict road networks. Edsger W. Dijkstra, a computer scientist, conceived it in 1956 and published it three years later. There are numerous variations of the algorithm. The original Dijkstra algorithm discovered the shortest path between two nodes, but a more frequent form fixes a single node as the "source" node and finds the shortest pathways from the source to all other nodes in the network, resulting in a shortest-path tree. Let us take a look at Dijkstra's Algorithm to find the shortest path between a given node in a graph to any other node in the graph:

   Let us call the node where we are starting the process as the initial node. Let the distance from the initial node to Y be the distance of node Y. Dijkstra's algorithm will begin with unlimited distances and attempt to improve them incrementally.

- Step 1: Mark all nodes that have not been visited yet. The unvisited set is a collection of all the nodes that have not been visited yet.
- Step 2: Assign a tentative distance value to each node: set it to zero for our first node and infinity for all others. The length of the shortest path discovered so far between the node v and the initial node is the tentative distance of a node v. Because no other vertex other than the source (which is a path of length zero) is known at the start, all other tentative distances are set to infinity. Set the current node to the beginning node.
- Step 3: Consider all of the current node's unvisited neighbours and determine their approximate distances through the current node. Compare the newly calculated tentative distance to the current assigned value and choose the one that is less. If the present node A has a distance of 5 and the edge linking it to a

  neighbour B has a length of 3, the distance to B through A will be 5 +3 = 8. Change B to 8 if it was previously marked with a distance greater than 8. If this is not the case, the current value will be retained.

- Step 4: Mark the current node as visited and remove it from the unvisited set once we have considered all of the current node's unvisited neighbours. A node that has been visited will never be checked again.
- Stop if the destination node has been marked visited (when planning a route between two specific nodes) or if the smallest tentative distance between the nodes in the unvisited set is infinity (when planning a complete traversal; occurs when there is no connection between the initial node and the remaining unvisited nodes). The algorithm is now complete.
- Step 5: Otherwise, return to step 3 and select the unvisited node indicated with the shortest tentative distance as the new current node.

It is not required to wait until the target node is "visited" as described above while constructing a route: the algorithm can end once the destination node has the least tentative distance among all "unvisited" nodes (and thus could be selected as the next "current"). For arbitrary directed graphs with unbounded non-negative weights, Dijkstra's algorithm is asymptotically the fastest known single-source shortest path algorithm with time complexity of O(|E| + |V|log(|V|)), where |V| is the number of nodes and|E| is the number of edges in the graph.

8. **Can we use the binary search algorithm for linked lists? Justify your answer.**

   No, we cannot use the binary search algorithm for linked lists.

   Explanation: Because random access is not allowed in linked lists, reaching the middle element in constant or O(1) time is impossible. As a result, the usage of a binary search algorithm on a linked list is not possible.

9. **What are recursive algorithms? State the important rules which every recursive algorithm must follow.**

   Recursive algorithm is a way of tackling a difficult problem by breaking it down into smaller and smaller subproblems until the problem is small enough to be solved quickly. It usually involves a function that calls itself (property of recursive functions).

   The three laws which must be followed by all recursive algorithms are as follows:

- There should be a base case.
- It is necessary for a recursive algorithm to call itself.
- The state of a recursive algorithm must be changed in order for it to return to the base case.
10. **Devise an algorithm to insert a node in a Binary Search Tree.**

An algorithm to insert a node in a Binary Search Tree is given below:

- Assign the current node to the root node.
- If the root node's value is greater than the value that has to be added:
  - If the root node has a left child, go to the left.
  - Insert node here if it does not have a left child.
- If the root node's value is less than the value that has to be added:
- If the root node has a right child, go to the right.
- Insert node here if it does not have the right child.
11. **Define insertion sort and selection sort.**
- Insertion sort: Insertion sort separates the list into sorted and unsorted sub-lists. It inserts one element at a time into the proper spot in the sorted sub-list. After insertion, the output is a sorted sub-list. It iteratively works on all the elements of an unsorted sub-list and inserts them into a sorted sub-list in order.
- Selection sort: Selection sort is an in-place sorting technique. It separates the data collection into sorted and unsorted sub-lists. The minimum element from the unsorted sub-list is then selected and placed in the sorted list. This loops until all of the elements in the unsorted sub-list have been consumed by the sorted sub-list.

Note: Both sorting strategies keep two sub-lists, sorted and unsorted, and place one element at a time into the sorted sub-list. Insertion sort takes the currently selected element and places it in the sorted array at the right point while keeping the insertion sort attributes. Selection sort, on the other hand, looks for the smallest element in an unsorted sub-list and replaces it with the current element.

12. **Define tree traversal and list some of the algorithms to traverse a binary tree.**

    The process of visiting all the nodes of a tree is known as tree traversal. Some of the algorithms to traverse a binary tree are as follows:

- Pre-order Traversal.
- In order Traversal.
- Post order Traversal.
- Breadth First Search
- ZigZag Traversal.
13. **Describe the heap sort algorithm.**

Heap sort is a comparison-based sorting algorithm. Heapsort is similar to selection sort in that it separates its input into a sorted and an unsorted region, then successively decreases the unsorted part by taking the largest element from it and putting it into the sorted region. Unlike selection sort, heapsort does not waste time scanning the unsorted region in linear time; instead, heap sort keeps the unsorted region in a heap data structure to identify the largest element in each step more rapidly. Let us take a look at the heap sort algorithm:

The Heapsort algorithm starts by converting the list to a max heap. The algorithm then swaps the first and last values in the list, reducing the range of values considered in the heap operation by one, and filters the new first value into its heap place. This process is repeated until the range of values considered is only one value long.

- On the list, use the buildMaxHeap() function. This function, also known as heapify(), creates a heap from a list in O(n) operations.
- Change the order of the list's first and last elements. Reduce the list's considered range by one.
- To sift the new initial member to its appropriate index in the heap, use the siftDown() function on the list.
- Unless the list's considered range is one element, proceed to step 2.

Note: The buildMaxHeap() operation runs only one time with a linear time complexity or O(n) time complexity. The siftDown() function works in O(log n) time complexity, and is called n times. Therefore, the overall time complexity of the heap sort algorithm is O(n + n log (n)) = O(n log n).

14. **What is the space complexity of the insertion sort algorithm?**

Insertion sort is an in-place sorting method, which implies it does not require any additional or minimal data storage. In insertion sort, only a single list element must be stored outside of the starting data, resulting in a constant space complexity or O(1) space complexity.

15. **What is the space complexity of the selection sort algorithm?**

Selection sort is an in-place sorting method, which implies it does not require any additional or minimal data storage. Therefore, the selection sort algorithm has a constant space complexity or O(1) space complexity.

**Conclusion**

So, in conclusion, we would like to convey to our readers that the Algorithm Interviews are usually the most crucial and tough interviews of all in the Recruitment process of a lot of Software Companies and a sound understanding of Algorithms usually implies that the candidate is very good in logical thinking and has the ability to think out of the box. Algorithm interview questions can be easily solved if one has a sound understanding of Algorithms and has gone through a lot of Algorithm Examples and Algorithm MCQs (which we will be covering in the next section of this article). Therefore, we suggest to all the budding coders of today to develop a strong grasp on the various Algorithms that have been discovered to date so that they can ace their next Technical Interviews.

[ref1]: Aspose.Words.1bd211e9-7a84-4e4e-8374-81842ef4ef1c.002.png
