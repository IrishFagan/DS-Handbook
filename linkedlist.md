# Linked List

**Linked List**: A linked list is composed of nodes that when continuously pointed towards the next node creates a list, which is therefore considered a linked list.

# In Memory

In memory, a linked list looks like this:

![Image of Linked List in Memory](images/linkedlist_memory.jpg)

Here are how both a Singly Linked List and a Doubly Linked List are displayed in memory.

# Operations

A Linked List supports the following operations:

* **Access**:
  * O(n), linear time. In order to access a specific value, we must still traverse every single node until we find the value that we're attempting to access.

* **Search**: Searches existing nodes for a provided value.
  * O(n), linear time. When searching a linked list for a specific value, there isn't any way to know where this specific value is at. The worst case scenario is going to be that the desired value is the last value in the linked list, therefore the operation is O(n).

* **Insertion**: Inserts a new node with a provided value.
  * O(1), constant time. Because of the way nodes store values and the addresses that they are pointing to next, insertion is fairly simple. A new node must simply be created, then point to a new node or null, and then have a previous node point to the new node. This assignment doesn't require any shifting or copying, therefore it is simply O(1).

* **Deletion**: Deletes a node with a provided value.
  * O(1), constant time. Much like insertion, all that must be done is change the addresses to which each node in the list points. The address being pointed to by the node being deleted must simply be reassigned to the previous node that originally was pointing to the node being deleted.

# Use Cases


A linked list is useful when simply inserting or removing nodes from the structure since these two operations are O(1).

A linked list is not as good as a BST or AVL Tree would be when having to access, search, insert and delete.

# Examples

~~~
list = UnorderedList()
list.search(3)
list.add(3)
list.remove(3)
~~~

[PREV PAGE](stack.md)

[NEXT PAGE](set.md)

(c) 2018 Michael Fagan. All rights reserved.
