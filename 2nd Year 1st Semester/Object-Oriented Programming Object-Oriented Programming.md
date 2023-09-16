# Lesson 1 Introduction to Object-Oriented Programming (OOP)

Real world entities for example inheritance hiding polymorphism 
bind together data Functions that operate on them

## Method declarations - (6 components)
1. Access modifier 
    - Public
    - Protected
    - Private
    - Default
2. The Return Type
3. Method Name
4. Parameter list
5. Exception list
6. Method body

> Object-oriented programming (OOP) is a way to organize and conceptualize a program as a set of interacting objects.
* Defines the types of objects that will exist.
* Creates object instances as they are needed.
* Specifies how these various object will communicate and interact with each other.

## An Object
Is a basic unit of Object-Oriented Programming that represents real-life entities
* State
* Behavior - represents the method in an program
* Identity - Unique name fir the object to interact with other object
* Method - connection of statement to do a specific task without returning anything.  Cane be reused code to save time.

>For example: Car - Color brand year speed


## Software Objects
Writhing software often involves 

## Software Object - Cont’d
In traditional programming languages data structures and procedures defined separately.
* In Object-Oriented programming they are defined together.
* Variables in an object are called attributes.
* Procedures associated with an object are called methods. 

## Classes 
A class is user-defined blueprint or prototype from which objects are created. It represents the set of properties or methods that are common to all objects of one type 
* Modifiers - can be public 
* Class name - capital letter for declaratyion
* Superclass (if any) - class parent
* Interfaces (if any) - uses keywords that use in programming languege
* Body - how the program works 

## Classes - Cont’d
* A class can be thought of as a template used to create a set of objects.
* A class is a static definition; a piece of code written in programming language.
* One or more objects described by the class are instantiated at runtime.
* The objects are called instances of class
* Each instance will have its own distinct set of attributes.
* Every instance of the same class will the same set of attributes;
    - Every object has the same attributes but,
    - Each instance will have its own distinct values for those attributes.

Bank example 
Class Account
Number;
Balance;
Deposite();
Withdraw();

# Object-Oriented Programming (OOP) Key Principles
> Aug 30

Class creation of data types

Method - makes it perform task or action in the program
If there no method there will be no action
Attribute - stores information about object and defines it

- __Encapsulation__ - the meaning of Encapsulation, is to make sure that _“sensitive”_ data is hidden from user.
- __Abstraction__
- __Inheritance__
- __Polymorphism__

__Encapsulation__ - the meaning of Encapsulation, is to make sure that _“sensitive”_ data is hidden from user.
Abstraction - 
Inheritance - 
Polymorphism - 

_Encapsulation example program in Java_
- Show example in picture from gravy

### __What is Data Hiding__
Data Hiding or information is a software development technique in object oriented programming which is used to hide the data from outside world. The purpose of data from misuse by outside world. Data hiding is also known as Data Encapsulation.

_Class example in picture_

Use getter and setters method to read and write value inside the class even on private class

## Why do we use data hiding?
- _Encapsulation and Abstraction_ - this prevent unauthorized access of the code
- _Information Hiding_
- _Maintenance and Refactoring_ - easier to change the class without destroying the whole code
- _Code Organization_ - using encapsulation clear separation on public method and private method within the class 
- _Flexibility and Extension_  - clear contact within the public interface also our internal implementation also change
- _Collaborative Development_ - using data hiding this get boundaries. Developer can work on specific part of code
- _Reduced Complexity_ - using class this reduced complexity. User don’t need to understand to 

Data hiding use make of good engineering principles

__How to achieve encapsulation in Java__
- Declare all your variables with private access modifier
- Create public getter and steer methods of those variable in order to allow access at those variable from outside the class.

__Advantages of Encapsulation__
- Security - 
- Flexibility - allows programer to change the code easily 
- Control - 
- Reusability - encapsulated code can be reuse across all application
- Maintainability - easier to maintain can be locate and be change code in program 



<p align=center>
    <i>Friday online class lang tayo</i>
</p>

_09/13/2023_
## Polymorphism

### What is Polymorphism in Java
- __Poly__ - many
- __Morph__ - forms/types

__Polymorphism__ in java is a mechanism in which an object to its behavior can have different forms.

```java
C —> B —> A
C ob = new C();
B b = c; or B b = new C();
A a = c; or A a = new C();
```


```java
class Animal {
  public void animalSound() {
    System.out.println("The animal makes a sound");
  }
}

class Pig extends Animal {
  public void animalSound() {
    System.out.println("The pig says: wee wee");
  }
}

class Dog extends Animal {
  public void animalSound() {
    System.out.println("The dog says: bow wow");
  }
}

class Main {
  public static void main(String[] args) {
    Animal myAnimal = new Animal();  // Create a Animal object
    Animal myPig = new Pig();  // Create a Pig object
    Animal myDog = new Dog();  // Create a Dog object
    myAnimal.animalSound();
    myPig.animalSound();
    myDog.animalSound();
  }
}
```

## How to check if an object is Polymophism
Any object which have more than one Is-A relationship will be 

## Benifits of Polymorhphism
- Code reusability
- Flexibility
- Simplier code

## Types of Polymophism
- __Complied-Time Polymophism__ _(static bonding)_ - This is achieved through method overloading and operator overloading
- __Run-Time Polymophism__ _(dynamic bonding)_ - This is achieved through method overiding and interface implementation.

## Compile time Polymophism
show pictures

## Parameter rules for method overloading in Java
- The number of parameters in both methods are different.
- Data type of parameters in both methods are different.

## What is Runtime Polymophism or dynamic binding
It is also known as dynamic meyhod dispatch. It is process in which a function call to the overridden method is resolved at Runtime.

show two pictures of code about run-time Polymophism

// end of disscussion