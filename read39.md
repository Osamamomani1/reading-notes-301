# Redux - Additional Topics


### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

The most ‘redux-like’ way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.

### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

You export the actual action from the reducer.

***

## Vocabulary Terms

* **Middleware**

software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.

* **Thunk**

middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises.