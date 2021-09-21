# < Login /> and < Auth />

## Why is the Context API useful?

enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.
***
## Can a component outside of a provider get its context?

No
***
## What are some common use cases for using the Context API?

* **them**
* **auth**
***
## what is“Context Hell”

 the nasty code you get taking advantage of the React Context API.
 ***

 # Vocabulary Terms

* **global state**

a way to pass data through the component tree without having to pass props down manually at every level, managing state in multiple components that are not directly connected

* **global context**

 designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

* **provider**

The component makes the Redux store available to any nested components that need to access the Redux store. Since any React component in a React Redux app can be connected to the store, most applications will render a at the top level, with the entire app's component tree inside of it.


* **consumer**

A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. Requires a function as a child. The function receives the current context value and returns a React node.

***