# Slideshow Four Notes
------
**Iterable Objects**
------
* Iterable objects are objects that can be iterated through similar to a sequence, such as strings and lists
  * We previously iterated through strings and lists, as well as accessed individual values using for loops instead of indexing
* **Note:** The portion of the object must be a sequence to be iterable, and something being iterable doesn't guarantee it's indexable
* 'iter' allows an object to be iterable and have the object call upon the method when the object is invoked, commonly just returning itself
* 'next' allows us to get to the next available value when iterating something
* It is common practice to set an index attribute to -1, increment it by 1 until self.index equals the sequence's length, and raise stopIteration when the end is reached
------
