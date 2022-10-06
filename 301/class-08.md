# Class 08

## API Design Best Practices

*1. What does REST stand for?*

Representational State Transfer (REST)

*2. REST APIs are designed around a ____.*

REST APIs are desgined around resources, which are any kind of an object, data or service that can be used by the client.

*3. What is an identifier of a resource? Give an example.*

An identifier of a resource is URL that uniquely identifies that resource. E.G, the URL for a certain customer might be;

https://adventure-works.com/orders/1

*4. What are the most common HTTP verbs?*

GET, POST, PUT, PATCH, and DELETE.

*5. What should the URIs be based on?*

A URI should represent a data object on the internet. It must be unique so its a one-to-one. One URI per one data object.

*6. Give an example of a good URI.*

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid

*7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?*

All web requests impose a load on the web server. The more requests, the bigger the load.

*8. What status code does a successful GET request return?*

A successful GET method typically returns HTTP status code 200 (OK).

*9. 









