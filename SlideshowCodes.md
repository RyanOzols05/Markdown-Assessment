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

------
**Slideshow Four**
------

------
