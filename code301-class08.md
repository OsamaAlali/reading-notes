    ## API Design Best Practices

  -  What does REST stand for? 
        > Representational State Transfer /architectural approach to designing web services
  -  REST APIs are designed around a ___resources_.

   -- What is an identifer of a resource https://adventure-works.com/orders/1    
-What are the most common HTTP verbs?

>   GET, POST, PUT, PATCH, and DELETE.

 -   What should the URIs be based on?

          based on nouns (the resource) and not verbs
  -  Give an examplehttps:

           //adventure-works.com/orders // Good of a good URI.

  -  What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
            web APIs that expose a large number of small resources

   - What status code does a successful GET request return? 200

   - What status code does an unsuccessful GET request return? 404

 -   What status code does a successful POST request return? 201

   - What status code does a successful DELETE request return? 204
