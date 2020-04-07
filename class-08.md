# Class-08
## Express Routing & Connected API


### Links
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)
- [Learn to Use the New Router in ExpressJS 4.0](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)


### Discussion Questions
1. **What is a benefit to using express.Router()?** you can modularize route and method handler middleware functions!
2. **When I say that top-down order matters in Express, what does that mean?** the file is read AND executed from top to bottom, so the order of your functions really matters.
3. **Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?** To make everything consistent. With this extra layer, it would be easier to change the wiring to a different database if need be, and developers could still use the same commands.


#### [Back to Home](README.md)