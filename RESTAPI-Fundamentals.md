*REST API FUNDAMENTALS*
=======================

What is an API Protocol?
 > An API protocol is like a set of rules or a language that helps two applications communicate and share information with each other. Think of it as a guidebook that ensures both sides understand the "conversation."
>
> Examples: REST, GraphQL, WebHooks, WedSockets, SOAP, RPC

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 *RESTful API (Representational State Transfer)*
   => is a way for applications to talk to each other over the internet using standard HTTP protocols.

 1. Stateless Communication
    > Each request from a client to the server is independent, and the server doesn’t store any information about previous requests.
    
    > Every time you send a request, you must include all the information the server needs to understand and respond.
    
    > Stateful communication examples: SOAP, Session-based APIs, RPC

 2. Lightweight
 3. Uses HTTP methods

Summary: REST is a architectutal style, it uses http protocol to do comminucation and is stateless and light weight.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

• REST APIs are like waiters in a restaurant—bridging the gap between your requests and the server's response.
 1. You tell the waiter what you want. (You make a request)
 2. And the waiter brings the food from the kitchen back to you. (You get your response back from server)

 Key Concepts of REST API :~

✅ Stateless: Each request to a REST API is independent. The server does not remember the state of previous requests.

✅ Data Format: Data is commonly exchanged in JSON, making it easy to understand and process.

✅ HTTP Methods: REST uses HTTP methods to perform operations on resources.

 • GET: Retrieve data.
 
 • POST: Create a new resource.
 
 • PUT: Update an existing resource.
 
 • PATCH: Partially update a resource.
 
 • DELETE: Remove a resource

✅  Let's imagine a simple API for managing a list of books:

GET /books: Retrieves a list of all books.

POST /books: Adds a new book to the collection.

GET /books/1: Retrieves the details of the book with ID 1.

PUT /books/1: Updates the information for the book with ID 1.

DELETE /books/1: Deletes the book with ID 1.
 
✅ HTTP Status Codes: REST APIs use status codes to indicate the result of a request

 • 200 OK: Successful operation.
 
 • 201 Created: Resource created successfully.
 
 • 404 Not Found: Resource not found.
 
 • 500 Internal Server Error: Something went wrong on the server.

 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
REST WITH EXAMPLES
==================

https://github.com/RachReddy/REST-API-101

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

