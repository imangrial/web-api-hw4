# web-api-hw4

Here is the link to the endpoint!!!
    http://onibakuman-test.apigee.net/v1/hw4/movies/

I have included a postman suite with this here. It will contain all of the necessary 
types of requests to test the proxy.

Note: I have kept the UUID's in the response so you can refer to each movie individually.
I will save the delete request in the postman suite but it only will delete the item once.

If its not tehre for whatever reason, you can delete it by performing a DELETE request to:
    http://onibakuman-test.apigee.net/v1/hw4/movies/<uuid>
The template will be in the postman suite.

All the resources are within the movies resource.

The fields are as follows
    title - movie title
    year - movie year
    actors - an array with 3 string values which correspond to the actors in teh film
    uuid - identifier for the movie instance

DELETE Request:
    Currently there are 6 entities in the BaaS. The movie "Six" is being pointed to by the delete request,
    So there still will be 5 entities after the delete at least.

GET Request: (Get Movie By UUID)
    This request is pointing to the movie "One". It will always return it

Thanks!
