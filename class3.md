## React Docs - lists and keys

1. What does .map() return?

 Return the output of the function inside it into an array(like take value from array make some changes on it then return it to another array).

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

Example:

```
function ListItem(props) {
  // Correct! There is no need to specify the key here:
  return <li>{props.value}</li>;
}

function NumberList(props) {
  const numbers = props.numbers;
  const listItems = numbers.map((number) =>
    // Correct! Key should be specified inside the array.
    <ListItem key={number.toString()} value={number} />
  );
  return (
    <ul>
      {listItems}
    </ul>
  );
}

const numbers = [1, 2, 3, 4, 5];
ReactDOM.render(
  <NumberList numbers={numbers} />,
  document.getElementById('root')
);
```

3. Each list item needs a unique `Key`.

4. What is the purpose of a key?
To identify which items have changed.

***

## The Spread Operator

1. What is the spread operator?

 new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements.

 spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

 2. List 4 things that the spread operator can do.

* Copying an array
* Concatenating or combining arrays
* Using Math functions
* Using an array as arguments

and

* Adding an item to a list
* Adding to state in React
* Combining objects
* Converting NodeList to an array

3. Give an example of using the spread operator to combine two arrays.

```
let array1 = [1,2,3]
let array2 = [4,5,6]
console.log([...array1, ...array2])
```
in the console :
```
[1,2,3,4,5,6]
```
4. Give an example of using the spread operator to add a new item to an array.

```
let array1 = [3, 4, 5];
let array2 = [1, 2, ...a]; 
```
```
then array2 = [1,2,3,4,5]
```

5. Give an example of using the spread operator to combine two objects into one.

```
let gamer = { name: 'Osama Momani', gender: 'Male' };
let gamestime = { game: 'league of legends', startfrom: '4 years' };
let gamercareer = {...gamer, ...gamestime};
/*
Object {
  "game": "league of legends",
  "startfrom": "4 years",
  "gender": "Male",
  "name": "Osama Momani",
}
* /
```

***

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?


creat a function and pass name object to it.


2. In your own words, what does the increment function do?

its loop throw the name objects and check if the name choosed in the new object match the name inside the old object then increase the counter for that name by one and return it to the new variable, then its updait the state of the old object.

3. How can you pass a method from a parent component into a child component?

passed as a prop to a child component.

4. How does the child component invoke a method that was passed to it from a parent component?

before the `render()`
```
this.prps.'name of the function'('teh thing you want to make change to')
```
and using onClick on the button

***


## Things I want to know more about 

* How to use map I dont think I get the full idea of it.
* more example about how to deal with state .



