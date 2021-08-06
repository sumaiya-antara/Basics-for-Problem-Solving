# Object Oriented Programming(OOP)
The aim of Object Oriented Programming is to bind the data and functions together that operate on them so that no other part of the code can access this data except that particular function.
Object-Oriented Programming is more secure than Procedure Oriented Programming(POP), because of the level of abstraction or data hiding property. It limits the access of data to the member functions of the same class.

# Procedural Programming vs Object Oriented Programming

![alt text](https://github.com/sumaiya-antara/Basics-for-Problem-Solving/blob/master/Class2/POP%20vs%20OOP.PNG "POP vs OOP")


# Class
A class is a blueprint that defines the variables and the methods(functions) common to all objects of a certain kind.

# Object
Object is an instance of a class. An object in OOP is nothing but a self-contained component which consists of methods and properties to make a particular type of data useful.

# Class vs Object
- In short, class is the prototype or design. When we create products from those deisgns, those products are objects.
- We can create thousands of objects from a class.
- No matter how many objects we create from a specific class, all those objects will have similar behaviour.

# 4 Basic Principles of Object Oriented Programming 
The four basic principles of Object-Oriented Programming are: Encapsulation, Abstraction, Inheritance and Polymorphism.

## Encapsulation
Encapsulation protects an object from unwanted access. Encapsulation binds together the attributes (data) and the methods (functions and procedures) that manipulate the data. It does this so that the data is protected. The attributes should only be accessed, retrieved or modified by using the methods that are encapsulated within the class definition.

Data should never be accessed directly. Instead, getter and setter methods must be provided that will allow access to the attributes:

- Getter methods return the value of an attribute
- Setter methods let us change the value of an attribute

## Abstraction
The main goal of abstraction is to handle complexity by hiding unnecessary details from the user. It shows only essential attributes and hides unnecessary information. Abstraction is selecting data from a larger pool to show only relevant details of the object to the user. It helps in reducing programming complexity and efforts.

## Inheritance
Inheritance is a mechanism in which one class acquires the property of another class. For example, a child inherits the property of his/her parents. With inheritance, we can reuse the fields and methods of the existing class. The idea behind inheritance is that we can create new classes that are built upon the existing classes. When we inherit from an existing class, we can reuse methods and fields of the parent class. Moreover, we can add new methods and fields in our current class also.
A child class must be inherited from the base class.

## Polymorphism
Polymorphism is a concept by which we can perform a single action in different ways. It occurs when we have many classes that are related to each other by inheritance. Polymorphism means one thing can take many forms.

The ways of doing polymorphism are-
- Duck Typing
- Operator Overloading
- Method Overloading
- Method Overriding


# Constructor
A constructor is a special method of a class or structure in object-oriented programming that initializes a newly created object of that type. The constructor is a method which is called automatically whenever an object is created. A constructor is like an instance method that usually has the same name as the class, and can be used to set the values of the members of an object, either to default or to user-defined values. This method is defined in the class and can be used to initialize basic variables.
If we create four objects, the class constructor is called four times. Every class has a constructor, but it is not required to explicitly define it.
In python, the constructor is created with the function **init** and it is represented in a dunder method like **__init__**

# Mutable and Immutable in Python
## Mutable
An object whose internal state can be changed is called a mutable object. In Python, **mutable** is the ability of objects to change their values. Usually, the objects that store a collection of data, are mutable objects and the values in those mutable objects can be changed, sorted or reversed.

Lists, Sets and Dictionaries are mutable.

## Immutable
An object whose internal state cannot be changed is called an immutable object. The state and values of an immutable object can never be modified after it is created.

Numbers(int, float, bool....), Strings, Tuples are immutable.

#### Note:
User-defined classes can be mutable or immutable depending on whether their internal state can be changed or not.

