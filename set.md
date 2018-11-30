# Set

A set is a structure that allows for many data types to be stored. This structure also doesn't allow duplicate items.

# In Memory

In memory, a set looks like this:

![Image of Set in Memory](images/set_memory.jpg)

# Operations

A Set supports the following operations:

* **Access**: Allows for access of a specified item or value.
  * O(n), linear time. Much like an array, a set is unordered. Even though a set has a pointer as well, items stored in the set are not always going to be the same size. Therefore, accessing items is not going to be a constant operation.

* **Search**: Allows us to search through the set and see if the provided value is present.
  * O(n), linear time. This operation is going to be linear as a result of having to search through all possible slots in order to find the specified item we are looking for. 

* **Insertion**: Allows us to add an item to the set, as long as the item being inserted is not a duplicate.
  * O(n), linear time. Because the list is unordered, there is no specified location for an item to be added to the set. Therefore, at worst we're going to have to copy items and then shift them over to accomodate for whatever item or value we are adding.

* **Deletion**: Simply removes an item from the set.
  * O(n), linear time. Much like insertion, items must be shifted in order to use the least amount of memory in the set. This is why this operation is linear.

# Use Cases

A set is useful when you would like to combine two structures and get rid of the duplicate values when joining the two structures.

A set is not as good as an array or list since a set is completely unordered and will automatically get rid of duplicate items, that might need to be stored for later.

# Examples

* **creation**:

~~~
mySet = {3,"dog",340000}
~~~

* **access**:

~~~
print(mySet[2])
~~~

* **search**:

~~~
5 in mySet
~~~

* **insert**:

~~~
mySet.add("froggg")
~~~

* **delete**:

~~~
mySet.remove(5)
~~~

[PREV PAGE](linkedlist.md)

[NEXT PAGE](tuple.md)

(c) 2018 Michael Fagan. All rights reserved.
