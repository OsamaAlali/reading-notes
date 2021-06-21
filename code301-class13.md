## Status Codes Based On REST Methods

1.	In your own words, describe what each group of status code represents:
•	100’s = informational status codes,hey usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
•	200’s =success codes, ell the client that its request was accepted
•	300’s =redirection codes, ell the client that the resource they are requesting isn’t available at the expected location anymore.
•	400’s =client error codes,  all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication,
•	500’s =server error codes, indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server
2.	What is a status code 202? used for asynchronous processing
3.	What is a status code 308? like the 202 code but using a Location header field in response to informing the client about the location of the created resource or an endpoint that lets the client check for the status of the creation process
4.	What code would you use if an update didn’t return data to a client? 204
5.	What code would you use if a resource used to exist but no longer does? 414 Request-URI Too Long
6.	What is the ‘Forbidden’ status code? 403 

## Build A REST: 
1.	Why do we need to pull our MongoDB database string out of our server and put it into our .env? Because when I want to publish my application i want to use other services 
2.	What is middleware? Its used between language as inter face 
3.	What does app.use(express.json()) do? make server accept JSON as body inside HTTP  methods
4.	What does the /:id mean in a route? Used in request
5.	What is the difference beween PUT and PATCH? PUT is update the entirety of a resource, PaTCH is  only update the user give it
6.	How do you make a default value in a schema? Used Default
7.	What does a 500 error status code mean? Error related to server 
8.	What is the difference between a status 200 and a status 201? 200 everything successes  but 201 is object created successfully 
