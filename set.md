# Set

A set is a structure that allows for many data types to be stored. This structure also doesn't allow duplicate items.

# In Memory

In memory, a set looks like this:

![Image of Set in Memory](images/set_memory.jpg)

Description

# Operations

A Set supports the following operations:

* **Access**: ?
  * O(?), ? time.

* **Search**: Allows us to search through the set and see if the provided value is present.
  * O(?), ? time.

* **Insertion**: Allows us to add an item to the set, as long as the item being inserted is not a duplicate.
  * O(?), ? time.

* **Deletion**: Simply removes an item from the set.
  * O(?), ? time.

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
