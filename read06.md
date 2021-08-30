# Authentication

### Explain what a “Singleton” is (in Computer Science terms)

A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.

### Explain how the Singleton pattern can be used with Node modules, specifically with classes

- The singleton pattern is used in programming languages such as Java and .NET to define a global variable. A single object used across systems remains constant and needs to be defined only once rather than many times.

- A singleton is intended to provide only one instance of itself while facilitating a global point of access. Implementing a singleton pattern involves creating a class with a method that creates a new instance of the class. In order to implement a singleton pattern, principles of single instance and global access must be satisfied.

- The singleton class is like a global repository for an instance of itself, making the constructor private. Therefore, an instance outside the class cannot be created at all, and a singleton can contain only one instance. A singleton class instantiates itself and maintains that instance across systems.

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

-  there is tow type of middelware the first one is global and the secound is to be scoupe or to specific route or end point

- so if i want to build one globel i will make a folder and put inside it 
the function i will use

- the function will be for all route and metode (get , post ,put, delete)

- the fuction take three parameter (request , response , next)

****

# Document the following Vocabulary Terms

* **Router Middleware**
Router is used to manage these incoming requests. It kind of routes your requests to correct handler/code

* **Dynamic Module Loading**

is a mechanism by which a computer program can, at run time, load a library or other binary into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.

* **Singleton Pattern** 

s a software design pattern that restricts the instantiation of a class to one single instance.

* **CRUD -> REST Method Matches**

 CRUD stands for Create, Read, Update, and Delete, which are four primitive database operations. At first glance, these operations map well to the HTTP verbs most frequently used in REST POST , GET , PUT ,DELETE

* **Mock Testing**

is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.

****
    