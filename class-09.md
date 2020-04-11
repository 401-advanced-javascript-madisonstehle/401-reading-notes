# Class-09
## API Server


### Links
- [Express app.param() Middleware](https://expressjs.com/en/api.html#app.param)
- [Express router.param() Middleware](https://expressjs.com/en/api.html#router.param)
- [Mongoose Middleware](https://mongoosejs.com/docs/middleware.html)
- [Mongoose Sub-Documents](https://mongoosejs.com/docs/subdocs.html)
- [Mongoose Virtual Joins](https://mongoosejs.com/docs/populate.html#populate-virtuals)


### Discussion Questions
1. **Describe a use-case where param middleware would come in handy.** If we're getting some sort of value as a param (such as an ID), then it would be useful to have a specific middleware that validated that piece of data.
2. **What are the two ways to add middleware in-between Mongoose and MongoDB interactions?** You can add app.param middleware and router.param middleware.
3 **What is the difference between a join by reference and a virtual join?** In a referential join, the id of the foreign key is referenced in the object. In a virtual join, you can have the name of what you're referring to in the object, and then you have a function go out and find that single record and populate it.
4. **What do localField and foreignField mean?** the localField is the the key label in the current object, and the foreignField is the key which the localField is referring to in the referred to collection


#### [Back to Home](README.md)