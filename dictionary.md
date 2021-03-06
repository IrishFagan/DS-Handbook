# Dictionary/Hash Table

A dictionary and hash table are structures that are not ordered and use keys to access values.

# In Memory

As a concept, a dictionary and hash table looks like this:

![Image of Dictionary/Hash Table in Memory](images/dictionary_memory.jpg)

# Operations

A Dictionary and Hash Table supports the following operations:

* **Get**: Accesses the value of the associated key that was provided.
  * O(1), constant time. This is operation is constant since it simply needs to return the value associated with the key.
  
* **Search**: Used to find whether or not a key and value pair are in the structure. If found will return the value associated with the key, other wise will return False.
  * O(1), constant time. Since the search operation must already be given a specified key, we will know whether or not if the key and value pair are in the dictionary. We then simply need to return the value associated with the key.

* **Insertion**: Can be used to add a key and value pair into the structure.
  * O(1), constant time. A dictionary or hash table isn't supposed to be thought of like a list or any type of ordered list, meaning insertion doesn't require any moving around of other values. The key and value pair are simply inserted into the bag of pairs.

* **Deletion**: Can be used to remove a key and value pair from the structure.
  * O(1), constant time. Since the delete operation is provied a key, the only thing that needs to be done is remove the pair.

# Use Cases

A dictionary or hash table are useful for finding specified keys, since the search operation is O(1) and most other structures are O(n).

A dictionary or hash table would not be as a good as a linked list when needing to consistently store a bunch of values. There is the possibility of a collision with the hash function.

# Examples

* **creation**:

~~~
myDictionary = {'Billy':5411231234,'Dog':'Bark'}
myDictionary.get(Billy)
myDictionary[Dog]
myDictionary['Cool'] = 'Dogs'
del myDictionary[Cool]
~~~

[PREV PAGE](tuple.md)

[NEXT PAGE](bst.md)

(c) 2018 Michael Fagan. All rights reserved.
