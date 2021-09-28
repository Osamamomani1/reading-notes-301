# Redux - Asynchronous Actions

1. How granular should your reducers be?

redycers should have an initial state and we can't change on it we just take some variebls form 
the state and change on it then return it 

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
it's depend on what you we

Well, it is a Pro more than a Con since we have to change multiple states in multiple components, the fact that all the reducers can listen when the action is dispatched can reduce a lot of work, each reducer can provide a different logic to the same dispatcher.

3. Name a strategy for preventing the above

Make a reducer for each component that will be affected by the dispatcher, only effecting a specific amount of the state it self.

***

## Vocabulary Terms

* **store** : a store holds the whole state tree of the application, the only way to change the state inside it is to dispatch an action on it, it is not a class , just an object with few methods on it.

* **combined reducers** : it is a helper function turns an object whose values are different reducing functions into a single reducing function we can pass to createStore.