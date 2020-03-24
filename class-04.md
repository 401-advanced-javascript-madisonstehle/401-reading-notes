# Class-04
## Advance Mongo/Mongoose


### Links
- [Testing Node.js + Mongoose](https://dev.to/paulasantamaria/testing-node-js-mongoose-with-an-in-memory-database-32np)
- [Introduction to Repository Design Pattern](https://cubettech.com/resources/blog/introduction-to-repository-design-pattern/)
- [NPM MongoDB-Memory-Server](https://www.npmjs.com/package/mongodb-memory-server)
- [NPM Supergoose](https://www.npmjs.com/package/@code-fellows/supergoose)
- [Mongoose Middleware Docs](https://mongoosejs.com/docs/middleware.html)
- [Compass](https://www.mongodb.com/products/compass)


### Vocabulary
- mock
- middleware
- supergoose
- pre hook
- post hook
- in-memory
- interface


### Discussion Questions
1. **What makes an interface useful?** It is a simplified way to enact more complex operations.
2. **Why is middleware called middleware?** Because it's in the middle! It's a "software between two other softwares" or a middleman between two operations.
3. **Fundamentally, what does it mean to have a mock of something? Why is this useful?** Since we wouldn't want to modify our actual data while testing, _mock_ data is basically "fake data" that should have the same models and formats as the real data would have.
4. **What does it mean to have a mock database?** A mock database would have the same structure, data models and commands as our application database. The mock database only exists during the lifetime of the test, though. It is created with fake data when we start our tests and deleted when tests are complete.



#### [Back to Home](README.md)