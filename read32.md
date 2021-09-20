# Context API - Behaviors

## When you have multiple contexts, what component type should you use (class/function) and why?

both work you can use whatever you wan't, for me I prefer to use function

***

## What are some good use cases for using the Context API for global state?

for authorization

***
## How can you best test context?

make tests unaware of its existence
***

# Vocabulary Terms

* **context** 
rovides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

* **useContext()**
used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level.

* **static context**

any file that is stored in a server and is the same every time it is delivered to users.
