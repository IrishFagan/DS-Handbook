# Binary Heap

A Binary Heap is a structure that allows for many data types to be stored. This structure also doesn't allow duplicate items.

# In Memory

In memory, a binary heap looks like this:

![Image of Binary Heap in Memory](images/binaryheap.jpg)

# Operations

A Binary Heap supports the following operations:

* **Search**: Is used to find the smallest or largest value, depending on whether it is a min or max heap.
  * O(n), linear time. 

* **Insertion**: Used to insert a node, which will then percolate to it's correct position, depending on the type of binary heap.
  * O(n), linear time. 

* **Deletion**: Used to remove a node, that then changes the structure of the tree.
  * O(n), linear time.  

# Use Cases

A Binary Heap is useful when needing to adjust a queue based on prioritization.

A Binary Heap is not as good as a Deque when needing to shift less important items around to multiple data structures.
# Examples

* **creation**:

~~~
BH = BinaryHeap()
~~~

* **search**:

~~~
BH.findMin()
~~~

~~~
BH.findMax()
~~~

* **insert**:

~~~
BH.insert(69)
~~~

* **delete**:

~~~
BH.delMin()
~~~

~~~
BH.delMax()
~~~

[PREV PAGE](graph.md)

[NEXT PAGE](queue.md)

(c) 2018 Michael Fagan. All rights reserved.
