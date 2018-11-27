# Tuple

A Tuple is a structure that can store many different types of data, but is immutable, meaning that it cannot be modified.

# In Memory

In memory, a Tuple looks like this:

![Image of Tuple in Memory](images/tuple_memory.png)

Description

# Operations

A Tuple supports the following operations:

* **Access**: ?
  * O(?), ? time.

* **Search**: Allows us to search through the tuple and see if the provided value is present.
  * O(?), ? time.

# Use Cases

A tuple is useful when multiple operations might need to access a piece of data at the same time, but we don't want any of the data to be modified.

A tuple is not as good as any mutable structure when needing to modify values on the fly.

# Examples