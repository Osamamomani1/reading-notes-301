# Advanced State with Reducers

## How can we ensure that an effect hook runs only once?

passing an empty array to the useEffect function
```
 useEffect(()=> {
        // any logice you want atach with th event or the value you want to see
    }, []);
```

***
## Can useState() update more than one state variable at the same time?


To store multiple values in useState, you have to put them into a single object, and be careful about how you update the state.
***
##  Is useState() synchronous?

useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components. Even though they are asynchronous, the useState and setState functions do not return promises.

***

# Document the following Vocabulary Terms

* **State Hook** A Hook is a special function that lets you “hook into” React features.

* **Component Lifecycle** as the series of methods that are invoked in different stages of the component's existence