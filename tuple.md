# Tuple

A Tuple is a structure that can store many different types of data, but is immutable, meaning that it cannot be modified.

# In Memory

In memory, a Tuple looks like this:

![Image of Tuple in Memory](images/tuple_memory.jpg)

# Operations

A Tuple supports the following operations:

* **Access**: Allows for access of all values by a provided index.
  * O(n), linear time. 

* **Search**: Allows us to search through the tuple and see if the provided value is present.
  * O(n), linear time.

# Use Cases

A tuple is useful when multiple operations might need to access a piece of data at the same time, but we don't want any of the data to be modified.

A tuple is not as good as any mutable structure when needing to modify values on the fly.

# Examples

* **creation**:

~~~
myTuple = (2,"cat",34)
~~~

* **access**:

~~~
print(myTuple[0])
~~~

* **search**:

~~~
34 in myTuple
~~~

[PREV PAGE](set.md)

[NEXT PAGE](dictionary.md)

(c) 2018 Michael Fagan. All rights reserved.
