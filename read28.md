# Component Lifecycle / useEffect() Hook

## Why do we not need more .html pages in a multi-page React app?

when we need to build multi-page websites in React we use multiple routes instead of multiple pages to handle multiple views
***
## If we wanted a component to show up on every page, where would we put it and why

Inside a `<Route />`

***
## What does routing do with the components that were rendered when a new route is requested

move from page to another one 

***

## What does props.children contain?

I'ts may contain elemnt more than one and nothiong

props.children is a special prop, automatically passed to every component, that can be used to render the content included between the opening and closing tags when invoking a component. These kinds of components are identified by the official documentation as “boxes”.
***
## How do useState() and this.setState() differ?

* setState is merging the previous state with the new one, it means that you dont have to pass the full state object every time you want to change some part of the state. React will update given properties and won’t touch the rest. 

* The useState’s updater rewrites a previous state with a new one and it does not perform any merging. Its just replacement instead of merging.

***

# Document the following Vocabulary Terms

* **State Hook :** 

 special function that lets you “hook into” React features. 

* **Mounting and Un-Mounting :**

The mount command mounts a storage device or filesystem, making it accessible and attaching it to an existing directory structure. The umount command "unmounts" a mounted filesystem, informing the system to complete any pending read or write operations, and safely detaching it

***