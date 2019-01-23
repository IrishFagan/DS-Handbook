# Graph

A graph is a structure that has nodes, which are connected by edges.

# In Memory

In memory, a graph looks like this:

![Image of Graph in Memory](images/graph_memory.jpg)

# Operations

A Graph supports the following operations:

* **Adding(Vertex)**: Adds a vertex into the graph.
  * O(1), constant time.

* **Adding(Edge)**: Adds an edge, connecting two provided vertices.
  * O(1), constant time.

* **Removal(Vertex)**: Deletes a vertex, which in hand disconnects edges.
  * O(|E|).
  
* **Removal(Edge)**: Deletes an edge that was connected between two vertices.
  * O(|V|).

# Use Cases

A graph is useful when needing to represent data visually, such as information between neighboring towns.

A graph would not be as good as a hash table or dictionary when needing to store an associated value with a key.

# Examples

* **creation**:

~~~
myGraph = Graph()
~~~

* **add**:

~~~
myGraph.addVertex()
~~~

~~~
myGraph.addEdge()
~~~

* **remove**:

~~~
myGraph.removeVertex()
~~~

~~~
myGraph.removeEdge()
~~~

[PREV PAGE](hashtable.md)

[NEXT PAGE](binaryheap.md)

(c) 2018 Michael Fagan. All rights reserved.
