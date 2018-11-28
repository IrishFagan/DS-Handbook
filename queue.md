# Queue

A queue is similar to a deque, but only allows for the queueing of values at the rear, and the dequeuing of values at the front. The way this data structure works is considered FIFO(First In, First Out)

# In Memory

In memory, a queue looks like this:

![Image of Queue in Memory](images/queue_memory.jpg)

# Operations

A Queue supports the following operations:

* **Access**: 
  * O(n), linear time.

* **Search**: Allows us to increment through the queue and determine if a provided value is present.
  * O(n), linear time.

* **Insertion**: Queues an item on the rear end of the queue.
  * O(1), constant time.

* **Deletion**: Dequeues an item on the front end of the queue.
  * O(1), constant time.

# Use Cases

A queue is useful when you need to regulate information being distributed. Queueing and dequeuing items allows for a quick insertion and deletion as well as O(1).

A queue would not be as good as a list, since accessing values is not as efficient.

# Examples

* **creation**:

~~~
myQ = Queue()
~~~

* **access**:

~~~

~~~

* **search**:

~~~

~~~

* **insert**:

~~~
myQ.enqueue(80000)
~~~

* **delete**:

~~~
myQ.dequeue
~~~

[PREV PAGE]()

[NEXT PAGE](queue.md)

(c) 2018 Michael Fagan. All rights reserved.
