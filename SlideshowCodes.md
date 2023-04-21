# Example Codes from the Slideshows
------
**Slideshow One**
------
Example Class
```python
class ClassName:
  pass
obj = ClassName()
print(obj)
```

Method Example
```python
class Person:
  def greet(self):
    print(‘Hello, how are you?’)
p = Person()
p.greet()
```

init Example
```python
class Person:
  def __init__(self, name):
    self.name = name
def greet(self):
  print(“Hello, my name is”, self.name)
p = Person(‘Barnaby von Fishlips’)
p.greet()
```
------
**Slideshow Two**
------
Student Class(Encapsulation Example)
```python
class Student1:
  def __init__(self,nameF, nameL, num):
    self.firstName = nameF
    self.lastName = nameL
    self.__studentNumber = num
  def __getStudentNumber(self):
    return self.__studentNumber
s1 = Student("Barnaby", "von Fishlips", 17)
print(s1.__getStudentNumber()) # Will cause an error
print(s1.__studentNumber) # Will also cause an error
print(s1.firstName) # Returns/Outputs “Barnaby”
s1.firstName = "Kensington"
print(s1.firstName) # Returns/Outputs “Kensington”
```
```python
class Student2:
  def __init__(self,nameF, nameL, num):
    self.__firstName = nameF
    self.__lastName = nameL
    self.__studentNumber = num
  def setFirstName(self, newName):
    self.__firstName = newName
  def getFirstName(self):
    return self.__firstName
```

Bear/Dog Classes(Overriding Example)
```python
class Bear:
  def sound(self):
    print("Groarrr")
class Dog:
  def sound(self):
    print("Woof woof!")
def makeSound(animalType):
  animalType.sound()
bearObj = Bear()
dogObj = Dog()
makeSound(bearObj)
makeSound(dogObj)
```

Illegal Overloading Example
```python
class Person:
  def __init__(self, name, age):
    self.__name = name
    self.__age = age
   def show(self):
    return self.__name
   def show(self, num):
    return "%s %d" % (self.__name, self.__age)
```

Dog Override Example
```python
class Dog:
  def __init__(self,name):
    self.__name = name
   def __str__(self):
    return “Woof, I’m %s.” % self.__name
corgi = Dog(“Tobasco”)
print(corgi)
```
------
**Slideshow Three**
------
Blank Single Inheritance Example
```python
class ParentClassName:
  # define parent class
class InheritanceClass(ParentClassName):
  # define inherited(child) class
  def __init__(self, param, param2):
    ParentClassName.__init__(self, param)
    self.param2 = param2
```

Person/Student Inheritance Example
```python
class Person:
  def __init__(self, name):
    self.__name = name 
  def getName(self):
    return self.__name
class Student(Person):
  def __init__(self, name, num):
    Person.__init__(self, name)
    self.__sNum = num
  def getStudentName(self):
    return("%s: %s" % (self.__sNum,self.getName()))
p = Person(“Barnaby von Fishlips”)
s = Student(“Charles”, “5623”)
print(p.getName()) # Output: “Barnaby von Fishlips”
print(s.getStudentName(), “and” , s.getName()) # Output: “5623: Charles and Charles”
```

Person/Student Inheritance w/ super() Example
```python
class Person:
  def __init__(self, name):
    self.__name = name 
  def getName(self):
    return self.__name
class Student(Person):
  def __init__(self, name, num):
    super().__init__(name)
    self.__sNum = num
  def getStudentName(self):
    return("%s: %s" % (self.__sNum,self.getName()))
p = Person(“Barnaby von Fishlips”)
s = Student(“Charles”, “5623”)
print(p.getName())
print(s.getStudentName(), “and” , s.getName())
```

Inheritance Polymorhpism
```python
class Parent:
  def method(self):
    pass
class Child(Parent):
  def method(self):
    # can be set to something else(polymorhped) but keep the same name
    pass
```
------
**Slideshow Four**
------
Deck of Cards(iter and next Example)
```python
class Deck:
  # Start of code
  def __iter__(self):
    return self
   def __next__(self):
    self.__index += 1
    if self.__index == len(self.__cards):
      self.__index = -1 # index reset
      raise StopIteration
    else:
      return self.__cards[self.__index]
  # Rest of the code
```
------
