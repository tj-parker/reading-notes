# Class 08 Reading Notes

## API Design Best Practices

REST stands for Representational State Transfer

REST APIs are designed around a resource, which are any kind of object, data, or service that can be accessed by the client

An identifier of a resource is a URI that uniquely identifies that resource

`
https://adventure-works.com/orders/1
`

The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE

The URI should be based on nouns (the resource) and not verbs (the operations on the resource)

`
https://adventure-works.com/orders // Good
`
`
https://adventure-works.com/create-order // Avoid
`

A "chatty" web API is one that exposes a large number of small resources. These should be avoided as they may require a client to send multiple requests, imposing a larger load on the server

A successful GET request returns HTTP status code 200

An unsuccessful GET request returns returns 404

A successful POST request returns returns 200 and includes the result of the operation in the response body. Alternatively, if there is no result to return the status code would be 204

A successful DELETE request returns 204
