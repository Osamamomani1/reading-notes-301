# Message Queues

### What does it mean that web sockets are bidirectional? Why is this useful?

enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

***

### Does socket.io use HTTP? Why?

socket.io server will attach to an HTTP server so it can serve its own client code through/socket.io/socket.io.js .

***

### What happens when a client emits an event?


To emit an event from your client, use the emit function on the socket object. To handle these events, use the on function on the socket object on your server. Sent an event from the client!

***

### What happens when a server emits an event?

the client side will receive the changes and got the results from what the event do.

***

* ### What happens if a client “misses” an event?

he wil not resive the result of that event 

* ### How can we mitigate this?

You could avoid missing an event by always having a separated file to contain the event action 
and this file or event will imited after the clint connect, and this event will imit the main event 
that we wan't to be sure that we will not miss

***

# Document the following Vocabulary Terms

1. **Socket :** one endpoint of a two-way communication link between two programs running on the network

2. **Web Socket :** is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. 

3. **Socket. IO :**  is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

4. **Client :**  is the medium through which clients access resources and services from a central computer

5. **Server :** server is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients". This architecture is called the client–server model. Servers can provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or performing computation for a client. A single server can serve multiple clients, and a single client can use multiple servers.

6. **OSI Model :**  `Open Systems Interconnection model` is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology. Its goal is the interoperability of diverse communication systems with standard communication protocols.

7. **TCP Model :** `Transmission Control Protocol` model is a suite of communication protocols used to interconnect network devices on the internet.

8. **TCP :** `Transmission Control Protocol` a communications standard that enables application programs and computing devices to exchange messages over a network. It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks.

9. **UDP :** `User Datagram Protocol` operates on top of the Internet Protocol (IP) to transmit datagrams over a network.

10. **Packets :** is a small segment of a larger message. Data sent over computer networks, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.