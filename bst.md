# Binary Search Tree

A Binary Search Tree is a structure that allows for quick searching, but also allows for fast insertion and deletion.

# In Memory

In memory, a Binary Search Tree looks like this:

![Image of Binary Search Tree in Memory](images/bst_memory.jpg)

# Operations

A Binary Search Tree supports the following operations:

* **Access/Search**: Uses a provided key to search for its relative node, and then return it.
  * O(log(n)), logarithmic time. Because of divide and conquer and the sorted nature of a Binary Search Tree, each step we take towards searching for a provided value cuts the possibilites in half. This makes this operation logarithmic.

* **Insertion**: A node with a key and value pair can be compared to each node in a tree until there is an empty place at the end of the tree.
  * O(log(n)), logarithmic time. In order to find out where we must insert a value, we must first use divide and conquer. Much like the search operation, the possibilities after each step is cut in half. Therefore this operation is logarithmic.

* **Deletion**: A node is removed in a specific way depending on it's placement inside the tree.
  * O(log(n)), logarithmic time. When deleting a value from the tree, we can use divide and conquer to half the possibilities by comparing the parent node to the value we are searching for and deleting. This allows for the operation to be logarithmic.
  
# Use Cases
 
A binary search tree is useful when needing to search for values relatively quickly. Divide and conquer allows for easy traversal, even with hundreds of values.

A binary search tree isn't useful in some circumstances when needing to store many values. A binary search tree's search operation can eventually become O(n), much like a linked list.

# Examples

* **creation**:

~~~
bst = BinarySearchTree()
~~~

* **access**:

~~~
print(bst[2])
~~~

* **search**:

~~~
"dog" in bst
~~~

* **insert**:

~~~
bst[41] = "dog"
~~~

* **delete**:

~~~
bst.remove(41)
~~~

[PREV PAGE](dictionary.md)

[NEXT PAGE](avltree.md)

(c) 2018 Michael Fagan. All rights reserved.
