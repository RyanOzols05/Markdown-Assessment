# Slideshow 3 Notes
------
**Inheritance**
------
* Inheritance is when an object or class is created off of another class, utilizing the features of that parent class
* Inheritance can branch like a tree(like a heirarchy) and/or be a hybrid by mixing the different types of inheritance
* When creating a child class, it will inherit all the attributes and methods that the parent had
* The child class can then create new methods/attributes that are unique to it, as well as override methods inherited from the parent
 * The child class does not need to use a new initialization method unless new attributes are to be created
 * Methods inherited from the parent only need to be reinstated if they've been overridden
* super() is a built-in method that allows child classes to refer to their parent class
* super() is used when new attributes are being created for a child class as it makes it so the preexisting attributes don't need to be recreated
------
**Types of Inheritance**
------
* Single Inheritance: A subclass inherits features from a single class/superclass
* Multiple Inheritance: A subclass inherits features from multiple classes/superclasses
  * Types of Multiple Inheritance:
   1. Multi-Generational: Grandparent --> Parent --> Child
   2. Multi-Parent: Parent A --> Child & Parent B --> Child
   3. Mixture of 1 and 2
* Multilevel Inheritance: A subclass inherits features from another subclass(A --> B --> C)
------
