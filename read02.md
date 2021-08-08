# Review, Research, and Discussion

### What’s the difference between PUT and PATCH?

The main difference between the PUT and PATCH method is that the PUT method use the request URI to supply a modified version of the requested resource which replaces the original version of the resource, where's the PATCH method supplies a set of instructions to modify the resource.

***
### Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
* [Postman ](https://www.postman.com/)
* [Stoplight ](https://stoplight.io/) 
* [Mocky.io ](https://designer.mocky.io/) 

***

### Compare and contrast Swagger and APIDoc.js Which HTTP status codes should be sent with each type of (un)successful API call

1. Swagger status Codes: 

* 200 : Successful request and response.
* 400 : Bad request
* 404 : Not found
* 500 : Unexpected error

2. APIDoc.js HTTP status Codes:

* 200 : Successful request and response.
* 400 : Bad request
* 404 : Not found
* 500 : Unexpected error

***

### Compare and contrast SOAP and ReST

 * SOAP(Simple Object Access Protocol)
 * REST (Representational State Transfer)

 1. Both SOAP and REST share similarities over the HTTP protocol, SOAP is a more rigid set of messaging patterns than REST. The rules in SOAP are important because we can’t achieve any level of standardization without them. REST as an architecture style does not require processing and is naturally more flexible. Both SOAP and REST rely on well-established rules that's all hav agreed to abide by in the interest of exchanging information.


 2. Differences:

    * for SOAP :Language, platform, and transport independent (REST requires use of HTTP). for SOAP :Works well in distributed enterprise environments (REST assumes direct point-to-point communication).

    * REST is more efficient (SOAP uses XML for all messages, REST can use smaller message formats). REST is faster (no extensive processing required). REST is closer to other web technologies in design philosophy.


![](https://i.stack.imgur.com/DFII3.png)

***

