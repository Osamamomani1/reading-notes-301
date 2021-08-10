# Review, Research, and Discussion

### Name 3 real world use cases where you’d want to change the request with custom middleware

1.  Hight-level payment method security

2. Track user behavior and stored

3. Handling error

***

### True or false: The route handler is middleware?

 **false.**

 *** 

 ### In what ways can a middleware function end the process and send data to the browser?

 Use of the next() **OR** with error handling.

 ***

 ### At what point in the request lifecycle can you “inject” middleware?

 After the request has been received.

 ***

 ### What can cause express to error with “Request headers sent twice, cannot start a second response” 

 when you send more than one request to the server and make interupt between this requests, the server will dell with this requests by send a response have an error.

 ***

 

