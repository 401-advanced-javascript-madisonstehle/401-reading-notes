# Class-03
## Data Modeling & NoSQL Databases


### Links
- [SQL vs NoSQL](https://www.xplenty.com/blog/the-sql-vs-nosql-difference/) (article)
- [SQL vs NoSQL](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y) (video)
- [MongoDB Docs](https://docs.mongodb.com/manual/)
- [Mongoose Docs](https://mongoosejs.com/docs/)
- [Data Modeling Explained in 10 Minutes or Less](https://www.credera.com/blog/technology-solutions/data-modeling-explained-in-10-minutes-or-less/)
- [MongoDB Atlas](https://docs.atlas.mongodb.com/)
- [Compass](https://www.mongodb.com/products/compass)


### Vocabulary
- database
- data model
- CRUD
- schema
- sanitize
- Structured Query Language (SQL)
- Non SQL (NoSQL)
- MongoDB
- Mongoose
- record
- document
- Object Relation Mapping (ORM)


### Discussion Questions
1. **Why would a developer choose to make data models?** Data modeling is a more planned and structured approach than simply creating variables on the fly. We can watch and regulate actions that may create or change the data.
2. **What purpose do CRUD operations serve?** CRUD (Create, Read, Update, Delete) operations are the way we can track our data modeling process. 
3. **What kind of database is Postgres?** Postgres is an SQL Database.
4. **What kind of database is MongoDB?** MongoDB is a NoSQL Database. It doesn't use a standard language and can use a variety of languages to access data.
5. **What is Mongoose and why do we need it?** Mongoose is a package that acts as a middleman between our app and our database. Mongoose will "translate" the JavaScript that we write it, and it will in turn translate that into something that MongoDB understands. Mongoose also adds some validity checking to MongoDB.
6. **Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the contraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.** For our 301 project, we did an app that created a date for yourself. In that app, there was User, Dates, and Category. Each Date would have a Category and belong to a User.



#### [Back to Home](README.md)