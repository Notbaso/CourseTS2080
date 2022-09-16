## What is object oriented programming?

The whole paradigm of object-oriented paradigm is the concept of objects. These objects contain data, which we also refer to as attributes or properties, and methods. Objects can interact with each other.

Object-oriented programming is based on the concept of objects. In object-oriented programming data structures, or objects are defined, each with its own properties or attributes. Each object can also contain its own procedures or methods.

Software is designed by using objects that interact with one another. This offers various benefits, like:

- being faster and easier to execute;
- providing a clear structure for a program;
- making code easier to modify, debug and maintain; and
- making it easier to reuse code.

## What are the basic concepts of OOP?

test

## What are the main principles of OOP?.

The main principles of object-oriented programming are encapsulation, abstraction, inheritance. 

## Encapsulation

The principle of encapsulation entails that all the properties and methods of an object is kept private and safe from interference by other objects. In each object we can have both private and public variables and methods. Private variables and methods cannot be called or used by other objects, whereas public ones can.

There are three basic techniques to encapsulate data in Object Programming. Data members, methods, and classes can all be encapsulated.
Types of Encapsulation in OOPs
Member Variable Encapsulation.
Function Encapsulation.
Class Encapsulation.

Why use Encapsulation? Encapsulation is used to hide the values or state of a structured data object inside a class, preventing unauthorized parties' direct access to them.

Security, data hiding simplicity, aesthetics


## Abstraction

Abstraction is the concept of object-oriented programming that "shows" only essential attributes and "hides" unnecessary information. The main purpose of abstraction is hiding the unnecessary details from the users.

Abstraction can be seen as an extension of encapsulation. Oftentimes, programs are very large with thousands of lines of code. This is difficult to maintain, but abstraction helps with this.

Abstraction means that every object only exposes a high-level mechanism for using it. Thus, the code within, to a large extent becomes irrelevant to other objects interacting with the object.

Using a game as example, the Attack method may have many lines of code contained in it. This code can specify how the hero can be attacked and what effect the attack may have on the health of the hero.

The enemy object does not need to be aware how the attack works, just that it works and that it reduces the health of the hero.

abstraction in real life: Facebook GUI, where you can use it without reading all the code.
abstraction importance: It helps in reducing programming complexity and efforts. dont burn out if you can use someones else project. 
prevent code repetition, improves flexibility, working in large team. 

## Inheritance

As stated before, programs often contain thousands of lines of code which is complicated and difficult to maintain. Another problem often encountered is that we have similar objects. They can share some code or logic, but they are not exactly the same.

If we had to create a brand-new object for every object we use in our program it would lead to more code and complexity. In order to prevent this, we can use inheritance. With inheritance we extract the logic in one object, called the parent, to another object, called the child.

Inheritance in OOP = When a class derives from another class. The child class will inherit all the public and protected properties and methods from the parent class. In addition, it can have its own properties and methods. 

importance inheritance is one of the most important aspects of Object Oriented Programming (OOP). The key to understanding Inheritance is that it provides code re-usability. In place of writing the same code, again and again, we can simply inherit the properties of one class into the other.

what is refactor code = edit code to make more readable
what is clean code = 

## Polymorphism

We have now seen how inheritance enables us to use a parent object to define a child object. The problem is that the child might have a different way of implementing a method.
Polymorphism gives us a way to use an object exactly like its parent but keeping its own methods as they are.
