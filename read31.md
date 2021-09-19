# Context API

## Describe use cases useState() vs useReducer() 

useState allows our functional components which used to be stateless become stateful. And useEffect allows our functional components leverage the component lifecycle hooks which were, in the past, only supported for class components

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.

***
## Why do custom hooks need the use prefix?

Custom hooks are normal JS functions, named with the prefix 'use', that can use hooks inside of it and contain a common stateful logic to be reused in other components.

***
## What do custom hooks usually do?

allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.

***
## Using any list of custom hooks, research and name one that you think will be useful in your applications

useScript React hook to dynamically load an external script and know when its loaded , useScript is a hook for loading and notifying when they’re loaded external scripts, dynamically.

*** 
## Describe how a hook that fetches API data might work

 you can use the useEffect than the method fetch with the url (its simller to axios and geting the data or request it )

***

# Vocabulary Terms

* **reducer** : useReducer is a React hook function that accepts a reducer function, and an initial state. ... This hook function returns an array with 2 values. The first one is the state value, and the second value is the dispatch function which is further used to trigger an action with the help of array destructuring