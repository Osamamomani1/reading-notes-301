# Combined Reducers

### Why choose Redux instead of the Context API for global state


So Redux works around the idea of having a central state called a store. To change the state, a component has to dispatch an action. The action is then passed on to the reducer, which changes the state of our application

***
### What is the purpose of a reducer?
to check all cases and change the state depend on them 

***
### What does an action contain?

Actions are the only source of information for the store as per Redux official documentation. It carries a payload of information from your application to store
***
### Why do we need to copy the state in a reducer?
In the documentation of reducers(read it again for details!), redux only requires our reducers to stay pure. If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part.

# Vocabulary Terms

* **immutable state** 

state have a constant value thats can't be changed

* **time travel in redux**

ability to move back and forth among the previous states of an application and view the results in real time.

* **action creator**

An action creator is merely a function that returns an action object.Calling an action creator does nothing but return an object, so you have to either bind it to the store beforehand, or dispatch the result of calling your action creator.

* **reducer**

A reducer is a function that determines changes to an application’s state. It uses the action it receives to determine this change.

* **dispatch**

dispatch is a function of the Redux store. You call store. dispatch to dispatch an action.
****