*API PROTOCOLS*
===============

1. REST: A way to get or send data over the internet using simple HTTP methods like GET or POST.

    > Example: GET /users retrieves a list of users.

2. GraphQL: A way to ask for exactly the data you need from a server in one request.

    > Example: Asking for a user’s name and email with a single query like query { user { name, email } }.

3. WebHooks: A way for one system to notify another system when something happens (usually in real-time).

    > Example: A payment system sending a webhook to your site when a payment is completed.

4. WebSockets: A protocol that lets you have an open, ongoing connection between the client and server for real-time updates.

    > Example: A chat app that updates your messages instantly.

5. SOAP: A protocol used for exchanging information in a strict format (usually XML) between computers.

    > Example: Sending a request to get customer details using XML format like <GetCustomer><ID>123</ID></GetCustomer>.

6. RPC: A method to call functions on a remote server, as if they were local to your computer.

    > Example: Calling a getUserInfo(userId) function on a remote server to retrieve user data.
