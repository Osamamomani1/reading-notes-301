## FUNCTIONAL PROGRAMMING

### What is functional programming?
Functional programming is a programming paradigm a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
***
### What is a pure function and how do we know if something is a pure function?
It returns the same result if given the same arguments (it is also referred as deterministic), It does not cause any observable side effects
***
### What are the benefits of a pure function?
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

* Given a parameter `A` → expect the function to return value `B`
* Given a parameter `C` → expect the function to return value `D`

A simple example would be a function to receive a collection of numbers and expect it to increment each element of this collection.

```
let list = [1, 2, 3, 4, 5];

let incrementNumbers = (list) => list.map(number => number + 1);
```
***
### What is immutability?
* immutability is Unchanging over time or unable to be changed.
* When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
***
### What is Referential transparency?
```
let duble = (x) => x + x;
```
This pure function will always have the same output, given the same input.
```
duble(4); // 8
duble(4); // 8
duble(4); // 8
```
Passing 4 as a parameter of the duble function will always returns 8. So now we can replace the duble(4) with 8. That's it, so our function is ```referentially transparent.```
***
## Things I want to know more about