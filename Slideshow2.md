# Slideshow Two Notes
------
**Encapsulation**
------
* Encapsulating information is hiding that information, restricting access to only certain attributes and/or methods
* This is done to protect the encapsulated information and choose how the information will be accessible
* Due to encapsulation not being possible in Python, the method used is putting a double underscore as a prefix
------
**Overloading and Overriding**
------
* Overloading: Two methods with different parameters have the same name within a single class
* Overriding: Two methods with different parameters have the same name but are within different classes(one in a parent class and one in a child class)
* Overriding allows the child class to utilize a method created in the parent class but implement the method differently
* It is possible to override built-in base-functions and built-in magic-methods
------
**Polymorphism and Inheritance**
------
* Polymorphism: A method utilizable in multiple classes and objects that is dependent on the given parameters
* Different non-inherited classes can have a method with the same name but different parameters
* Overloading is illegal in Python but is still a type of polymorphism
* Inherited classes modifying an inherited method is an example of overriding
------
**Base Overrides**
------
* There are two fundamental concepts to understand when it comes to overriding and polymorphism in Python.
1. Two different classes can have the same attributes and methods as one another
2. A child class can have a method from the parent class that has been overridden so the child class can use it differently
* There are some benefits to overriding built-in methods and operators, which are:
  * It's possible to complete mathematical operations on custom objects
  * It's possible to compare equality between custom objects
  * You can manipulatehow objects behave when they're met with built-in operators and methods
------
**The ```__repr__``` Function**
------
* ```__repr__``` provides a printable version of custom objects
* ```__str__``` provides a string version of custom objects
* In order to make custom objects printable you must override both ```__repr__``` and ```__str__```
------
