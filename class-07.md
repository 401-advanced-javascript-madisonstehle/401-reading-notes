# Class-07
## Express


### Links
- [Express Middleware Explained](https://www.youtube.com/watch?v=9HOem0amlyg)
- [Using Express Middleware](https://expressjs.com/en/guide/using-middleware.html)
- [Express Middleware](https://www.tutorialspoint.com/expressjs/expressjs_middleware.htm)
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)
- [Supertest](https://github.com/visionmedia/supertest)
- [Express Middleware List](https://expressjs.com/en/resources/middleware.html)
- [HTTP Status Codes](https://www.restapitutorial.com/httpstatuscodes.html)


### Vocabulary
- Express
- endpoint
- routing
- query
- event
- application middleware
- route middleware
- error middleware


### Discussion Questions
1. **What code does the server actually run?** I'm a little confused as to what this question is asking? The server runs the code we give it. We will use an Express package to write "JavaScript" using Express terms. Express is middleware that is called in-between the request and response.
2. **What Express/HTTP operations map to CRUD operations?** `GET` = `READ`, `POST` = `CREATE`, `PUT` = `UPDATE`, `DELETE` = `DELETE`
3. **What does `res.send()` do?** Sends the response data back to the client in the properly formatted way.
4. **What is the order of operations for the three categories of middleware (handler, application, route)?** Application runs whenever the server receives a request, Route runs whenever the server receives a request to a specific URL endpoint, and Handler runs when the server receives a specific method request to a specific route.
5. **What is the parameter `next` used for?** It will call the next middlewhere in the chain.


#### [Back to Home](README.md)