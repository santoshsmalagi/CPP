# Programming Paradigms
Programming paradigms are a way to classify programming languages based on their features. A paradigm is a model or a framework for describing how a program handles data. There are several possible programming paradigms, the major ones are:

* **Procedural (or imperative) Paradigm**
  * Problem is viewed as a sequence of procedures
* **Object-Oriented Paradigm**
  * Approach that provides a way of modularizing programs by creating partitioned memory area for both data and functions, and can be used as a template for creating copies of such modules on demand.
* **Functional Paradigm**
  * Treats computation as the evaluation of mathematical functions 
* **Logical Paradigm**
  * Programming by specifying a set of facts and rules, an engine infers answers to questions

> *Many programming languages cannot be strictly classified into one paradigm, but rather include features from several paradigms.*

# Procedural (Imperative) Paradigm
* **Characteristics**
  * The problem is broken down into smaller parts, implemented as a sequence of instructions which are logically grouped together in the form of functions or sub-modules
  * Data (often shared between functions) is organized in the form of data structures
  * Functions have hooks - defined interfaces for data access, and modify or operate on this data. This data can be passed on to other functions for further processing.
  * Sequence of operations is repeated till the intended goal is achieved
  * Emphasis is on the procedure or algorithm (way of doing things)
  * Employs top-down approach to program design
* **Drawbacks**
  * Global data moves freely around the system, and hence is vulnerable to change
  * A revision of a data structure must reflect across all functions which make use of this data
  * There is no explicit relationship between the functions and data structures, to solve a problem, we need to choose the data structure and then go and find the appropriate function(s) to be applied to it.


# Object-Oriented Programming Paradigm
* **Characteristics**
  * The functions that can be applied to a particular type of data structure are packaged with the data - this package is referred to as an *object*
  * Multiple copies or instances of same object type store data in their respective memory partitions, and all objects of the same type share the functions
  * Data does not flow freely in the system since it is only accessible by the functions associated with that object type, in this way it is protected from accidental modification - i.e. data is hidden (data encapsulation)
  * Objects communicate with each other via functions (message passing)
  * Emphasis is on the data rather than the procedure
  * Employs bottom-up approach to program design
  
## Basic concepts of OOP:
* **Objects**
  * Basic runtime entities in an object oriented system
  * Programming problems analyzed in terms of the objects and nature of the communication between them
  * Occupy memory and have an associated address
  * Objects interact by sending messages to each other, without having to know the internal details of each other's code or data
  * Suffices to know the type of message or response accepted
* **Classes**
  * The data and the associated functions can be grouped together and made a *user-defined* type using a class
  * *Objects* are nothing but variables of type *class*
  * Once a class is defined, multiple objects of type class can be created
* **Data Abstraction and Encapsulation**
  * The wrapping up of data and functions into a single unit (aka *class*) is known as *data encapsulation
  * Data is not accessible to the outside world and only those functions which are members of the class can access it
  * Functions provide a means to interact with the object's data 
  * Insulation of data from direct access by a program is called *data hiding* or *information hiding*
  * *Data abstraction* - refers to the process of only representing the essential information while hiding the background details
  * Attribute - refers to the data members of a class
  * Functions which operate on these attributes (data members) - are called member functions of the class or methods
  * So classess hide the attributes (data members), encapsulate the data and operators (functions) hence also called as - *Abstract Data Types*
* **Inheritance**
* **Polymorphism**
* **Dynamic Binding**
* **Message Passing**



> *A language is said to support a style of programming if it provides facilities that make it convenient (reasonably easy, safe, and efficient) to use that style. A language does not support a technique if it takes exceptional effort or skill to write such programs; it merely enables the technique to be used. For example, it is possible to write structured programs in FORTRAN and Object-Oriented programs in C, but it is unnecessarily hard to do so because these languages do not directly support those techniques.*

## Common programming languages and paradigms supported by them:

* **C** - mostly an imperative or procedural programming language, but can implement OOP concepts (which is not very efficient)
* **C++** - mostly intended as an object-oriented programming language, though C++ can also be written as pure procedural programs
* **Python** - supports imperative (procedural), functional, and object-oriented programming
* **Shell-Scripting** - though shell-scripting does not really fall into the category of mainstream programming languages (it is a scripting language), it is imperative or procedural programming
* **Tcl** - supports multiple programming paradigms - object-oriented, imperative and functional programming styles.

Add images to illustrate both the programming paradigms
all OOP concepts as one liners until section 1.6.
