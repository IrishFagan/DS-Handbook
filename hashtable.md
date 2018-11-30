# Hash Table

A hash table is a structure that uses a hash function to convert a key into a value.

# In Memory

In memory, a hash table looks like this:

![Image of Hash Table in Memory](images/hashtable_memory.jpg)

Description

# Operations

A Hash Table supports the following operations:

* **Search**: Uses a key value to find the hashed value.
  * O(n), linear time.

* **Insertion**: Stores a key and value pair that can then be looked up later on.
  * O(n), linear time.

* **Deletion**: Removes a key and value pair from the structure.
  * O(n), linear time.

# Use Cases

A hash table is useful when storing passwords or phone numbers that need to be associated with a user or person.

A hash table is not as good as a list when constantly needing to access values.

# Examples

* **creation**:

~~~
HT = HashTable()
~~~

* **access**:

~~~
print(HT[30])
~~~

* **search**:

~~~
HT.get(dog)
~~~

* **insert**:

~~~
HT[7] = "cat"
~~~

* **delete**:

~~~
del HT[7]
~~~

[PREV PAGE](avltree.md)

[NEXT PAGE](graph.md)

(c) 2018 Michael Fagan. All rights reserved.
