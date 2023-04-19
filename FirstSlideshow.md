# Slideshow One Notes

**Definitions**
------
* State: Characteristics; the measurable data
* Behaviour: Available functionality(what the object can do)
* Attribute: Data of an object; the accessible tools of an object
* Method: Code of an object; functions that can be called by an object or class
* Field: Variable that belongs to either an object or a class
------
**Object Oriented Programming**
------
* OOP designs programs object creation in mind and is meant to design modular & reusable programs/software
* The goal of OOP is to create an object that can be defined and will function in a way that will help solve problems
------
**OOP vs POP**
------
* OOP focuses more on the definition on data than input --> processing --> output logic like procedure-oriented programming does
* POP: A human may require calculations, completiong of repetitive tasks, databases, and logical evaluations
* OOP: When creating a human object, you consider their name, address, and what they can do
* OOP focuses on how you manipulate an object's data rather than the logic behind the manipulation
------
**Objects**
------
* An object in Computer Science(CS) can be a variable, method, data structure, or function; it has an in-memory location that has a value referenceable by an identifier
* An object in OOP, similarly to CS, is a class instance where the object can be a function, variable, data structure, or a combination of said data types
* An object is a combination of functional code and data since real-world objects have states and behaviours
------
**Example Object: Dog**
------
* Dog could have the attributes of name, colour, breed, isHungry, and isThirsty
* Dog could have the methods of bark(), sleep(), and eat()
* If we populate the attributes of Dog then we have instances, which means we have objects
------
**Classes**
------
* A class is an abstract description of all objects that can be created by a class that instantiates objects.  Classes also contain attributes, fields, and methods.
* There are two types of fields: One that belongs to an instance of a class, and one that belongs to a class itself
* 'class' is a built-in keyword in Python that allows the user to create their own class
* To create a class, the user must:
1. Define the class' name using the 'class' keyword
2. Define the attributes of the class inside the class' code block
3. Assign a variable that has an instantiation of the class so the class is interactable
* Methods for a class can be declared in the same way you would normally declare a new function
------
**The init Method and 'self'**
------
* The initialization(init) method is executed once a class' object is instantiated, which helps to initialize the attributes of an object
* The 'self' parameter is used to inidcate that the method is applicable to the object itself
* 'self' also treats its own attributes as local attributes
------
**List is an object**
------
* L = [1, 2, 3, 4]    L is an instance of a list class, meaning L is an object
* Features:
  * L[i] --> indexing      L[i:j] --> slicing
  * Functions --> len(), min(), max()
  * Operators --> + and *
  * Methods --> L.append(), L.count(), L.extend(), L.sort(), L.reverse()
 * It's needed to be known that the above features are coded so long as we know what list can do
------
