# Class 07

## How I explained REST to my brother

1. Who is Roy Fielding?

He helped write the first web servers, that sent documents across the internet and he did lots of research and writing as to how the web works the way it does.

2. Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

It wasn't designed to be used like this. being able to talk to any machine in the world was a primary concern.  Most of the techniques developers used later to get computers to talk to each other didn't have those requirements. You only needed to be able to talk to a small group. 

3. What is the HTTP protocol that Fielding and his friends created?

The HTTP protocol that Fielding and his friends created is all about applying verbs to nouns. For instance, when you go to a webpage, the browser does a HTTP GET and it returns as a webpage.

4. What does a GET do?

GET is used to request data from a specificed resource

5. What does a POST do?

POST is used to send data to a server to create/update the resource. The data sent to the server with POST is stored in the request body of the HTTP request.

6. What does PUT do?

PUT is used to send data to a server to create/update a resource. The difference between POST and PUT is that PUT requests are idempotent. That is, calling the same PUT request multiple times will alawys produce the same result. In contrast, calling a POST request repeatedly have side effects of creating the same resource multiple times. 

7. What does PATCH do?

The PATCH method is used to apply partial modifications to a resource.
