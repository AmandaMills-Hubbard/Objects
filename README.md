# All About Objects
 

##Objects##
Created By Thais Nascimento, Elmer Osorio Jr, Ilunga Lebreton, Abigail Ezedonmwen, Sebastian vivas, Amanda Mills-Hubbard

##Description##

JavaScript has two data types, primitive and reference. Primitive data types consist of booleans, strings, numbers, null, undefined, and symbol. Objects are reference data types which is what we’ll be focusing on.
An object is a collection of related data which usually consists of several properties and methods. The way an object’s data is stored is in the form of key: value pairs. 
Key/Value pairs represent strings and values, values can be further broken down and be categorized as methods, which are known as functions. This is why functions are classified as objects in javascript.

## Properties ##

We often hear the word “properties” in Javascript. Reference types all contain properties, but an **object’s** properties are made of strings instead of numbers. These properties point to different elements or **values** in an object. To better understand this, let’s look at an example:

**We have a const variable that contains the string, ‘We out here’.**

_const gardner = ‘We out here’;_

**Let’s place it in a string object.**

_const gardner = new String ( ‘We out here’);_

_console.log(Object.key(gardner).length);_

Notice the property **.length** highlighted in the example. Properties are preceded by a dot operator. This allows you to access the property in Javascript, without it, the property will not initialize. Properties do not contain parameters, so they will never contain a set of parentheses at the end. The property .length, in this case, allows you to retrieve the length or total of a string object. The return would be 11, for the total amount of characters, including spaces, in the string, ‘We out here’. There are several properties at your disposal built into Javascript. Familiarize yourself with the syntax for properties, this will help you build objects. Next, let's take a look at **methods**. 

##Deleting a property from an object## 

-The **delete** operator deletes a property from an object. When deleted, it will return true, else false will be returned.
-To remove an operator from an object you must use the delete operator.
-The operator is only removed if there is nothing held to it.
-Another way to delete property from an object is to set it to  undefined .The property will still remain in the object. It will just have a value that is undefined.

**Syntax for using delete operator:**
-Delete object.property
-Delete object['property']

**Syntax for setting an object to undefined:**
- MyObject.propertyB=undefined 

## Object-Oriented Programming ##
* What is OOP?
  * Object-oriented programming (OOP) is a way of writing computer programs which is using the idea of "objects" to represent data and methods.
* Why is OOP useful?
  * OOP allows us to redefine and manipulate the properties/values of an object. 
* The Basics, the Four Pillars of OOP:
  * Encapsulation: When an object has various properties grouped together under functionality. 
  * Inheritance: When an object inherits other properties from another object. 
  * Polymorphism: When an object share similar properties under different programming environments
  * Abstraction: When an object hides unwanted details while showing the most essential property values.
* Encapsulation:
  * Example: user form. A form captures information about a person and can be created into key-value data properties.
  * Popular methods used: Object Constructor
  ![Encapsulation]()
* Inheritance:
  * Example: a button that has similar properties but may have a different text inside the button itself or same color; different sizing
  * Popular Methods used: Prototype
  ![Inheritance]()
* Polymorphism:
  * Example: having one object called shape within one interface but has multiple function like circle, rectangle, triangle.
  * Popular Methods used: Extends
  * ![Polymorphism]()
* Abstraction:
  * Example: Calculate the area of shapes for different shapes, only writing the function once within the global environments.
  * Popular Methods used: document.write and Math.sqrt
  * ![Abstraction]()

## Creating Objects ##

You can create objects in JavaScript using a constructor function or using the Object.create method. 

### Constructors:
When an object is created using a constructor, the value of the object is in reference to the function itself. Classes are used to reuse certain functionalities that pertain to all the objects being created while also allowing for abstraction in specific objects. For example, a group of people could all work in the same building but on different floors and offices. Also, the objects can inherit characteristics from previous objects. 

### Object.create method

When an object is created using this method, it is made based on a previous object otherwise known as the prototype.  Properties can then be overwritten using the argument Object.defineProperties().

##Constructors##
-Constructor function creates objects 
-Value of the object in reference to the function itself
-Classes are used to reuse certain functionality but allow for abstraction when it comes to specific objects 
-Objects can inherit characteristics from other objects

-Other ways to create
-Object.create method- uses already existing object as prototype

##Methods##

_Methods can be confusing to understand at first. Here are a few examples that break it down in the simplest form._
                                                  *Primitive Methods* 
_ Although they’re primitive type strings, numbers, and Booleans have methods._

_ However nuLL and undefined types have no methods but they are still primitive._

 _All primitives are unchangeable meaning they cannot be altered._

                                    *Object Methods*
 _Whenever a property value is a function, the property is considered a method._

 _you can also add a method to an object in the same way that you would add a property._
 
_ You can call a method directly from an object as for example person.sayName(“Name”)._                           
