# Review, Research, and Discussion

### What is the benefit of transforming data into packets?

TDM-based networks must transform into packet-based networks to meet the demands of pervasive data-centric applications and services.

Packet-based networks not only enable new innovations, services, and business opportunities, they are also the most cost-effective, efficient, and scalable networks for content delivery.

***

### UDP is often refereed to as a connectionless protocol. Why is this?

is a connectionless protocol and its known as datagram protocol because it is analogous to sending a letter where you don't acknowledge receip.

***

### Can a socket server application have multiple socket connections?
Yes

***
### Can a socket connection application be connected to multiple socket servers

Yes 

***

### Can an application be both a socket server and a socket connection?

 Most applications that use both a client and server socket will be multithreaded. The reason for this is simply because the server needs to listen continuously to the port that it is connected to. In the meantime, the rest of the application will need to continue, sending messages through the client socket and doing whatever else needs to be done. Often, the client socket would also run in its own thread so sending data over it won’t block the execution of the main application. The main difference between a client and server is that the server is continuously waiting for a client to connect so data can be exchanged by both. The client is generally just making quick connections and will close again so the client port can be used for another task.
***
 # Document the following Vocabulary Terms

* **observer pattern** : A software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

* **Listener**:The event listener is a hook in the event method that’s called on each event firing that calls the event handler

* **Event Handler**: scripts that are automatically executed when an event occurs. Event handlers are embedded in documents as attributes of HTML tags to which you assign JavaScript code to execute

* **Event Driven Programming**: A programming paradigm in which the flow of program execution is determined by events

* **Event Loop**: The event loop is the secret behind JavaScript’s asynchronous programming. … The event queue is responsible for sending new functions to the track for processing.

* **Event Queue**: Is responsible for sending new functions to the track for processing. It follows the queue data structure to maintain the correct sequence in which all operations should be sent for execution.

* **Call Stack**:  is responsible for keeping track of all the operations in line to be executed. Whenever a function is finished, it is popped from the stack.

* **Emit/Raise/Trigger**: method is used to trigger the event.

* **Subscribe**: The .subscribe() function is similar to the Promise.then(), .catch() and .finally() methods, but instead of dealing with promises it deals with Observables.

* **database**: it’s implements a common, promise-based interface for SQL database access. Inspired by Java, it uses connection strings to identify the database driver. Wrappers around native database drivers provide a unified interface to handle databases

***