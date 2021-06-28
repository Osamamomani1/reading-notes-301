## API Design Best Practices

1. What does REST stand for?

Representational State Transfer

2. REST APIs are designed around a `resources`

3. What is an identifer of a resource? Give an example.

resource has an identifier, which is a URI that uniquely identifies that resource. For example
https://adventure-works.com/orders

4. What are the most common HTTP verbs?

 GET, POST, PUT, PATCH, and DELETE.

 5. What should the URIs be based on?

 resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource)

 6. Give an example of a good URI.

 https://adventure-works.com/orders // Good 


 7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

 "chatty" web APIs that expose a large number of small resources, its a bad 

 8. What status code does a successful GET request return?

 status 200 

 9. What status code does an unsuccessful GET request return?

 status 404

 10. What status code does a successful POST request return?

 201 Created

 11. What status code does a successful DELETE request return?

 204

 ***

 ## Things I want to know more about
 wish if we could get more explnation about api in coding I feel like i miss the main idea sometimes 