# Stack

A stack is a data structure that is not ordered but only has one end that can be modified. Items can neither be added to the bottom or middle of the structure. The way this structure behaves is called LIFO(Last In, First Out).

# In Memory

In memory, a stack looks like this:

![Image of Stack in Memory](images/stack_memory.jpg)

Here we can see the application of a LIFO(Last In, First Out) structure.

# Operations

A stack supports the following operations:

* **push**: Places an item at the top of the stack.
  * O(1), constant time. Because of the stack pointer keeping track of the top of the stack, all that needs to be done is increment and then add an item to the top. This is why this operation is simply O(1).

* **pop**: Returns the item at the top of the stack.
  * O(1), constant time. This operation is constant thanks to the stack pointer being based at the top of the stack. The only work the pop operation must do is simply return the value stored at the stack pointer. We don't need to peek inside to return it, which is why it isn't O(n).

* **peek**: Returns the item at the top of the stack without removing it or cahanging the stack pointer.
  * O(1), constant time. This operation is constant because it always knows where the top of the stack is, which is the location of the only value that can be peeked at. It should always be a constant time to access the top value.

# Use Cases

A stack is useful when needing to backtrack or see history in a program. Each operation done in a program can be simply pushed onto the stack and then be accessed by popping it off of the stack.

It is not as good as storing hundreds of values that might need to be accessed at any time. We can only access the top value, which means if our desired value was at the bottom we would have to pop everything else off to access just a single value.

# Example

* **creation**:

~~~
Stack()
~~~

* **push**:

~~~
push(item)
~~~

* **pop**:

~~~
pop()
~~~

* **peek**:

~~~
peek()
~~~

[PREV PAGE](array.md)

[NEXT PAGE](linkedlist.md)

(c) 2018 Michael Fagan. All rights reserved.
