# Class-02
## Classes, Inheritance, Functional Programming


### Links
- [Why Use Static Types in JavaScript? Advantages and Disadvantages](https://www.freecodecamp.org/news/why-use-static-types-in-javascript-part-2-part-3-be699ee7be60/)
- [What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)
- [Inheritance and the Prototype Chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
- [`this`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
- [Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [Node.js Error Documentation](https://nodejs.org/dist/latest-v6.x/docs/api/errors.html)


### Vocabulary
- **functional programming**: A way of thinking about the functions we write - they should be pure, have no shared state (one function doesn't effect how another one runs), and immutable. We want our functions to be efficient and predictable.
- **pure function**: A function given the same input should return the same output
- **higher-order function**: A function that takes another function as an argument and/or returns a function
- **immutable state**: Don't modify the arguments or return value outside of function
- **object**: 
- **object-oriented programming (OOP)**:
- **class**: A specific classification upon data - a blueprint for how the data should look. We then create _instances_ of that class.
- **prototype**:
- `super`:
- **inheritance**:
- **constructor**:
- **instance**:
- **context**:
- `this`: a keyword that refers to the current instance. a placeholder used to write the blueprint!
- **schema**: an object used to validate objects. Each key is a key we expect to see in our valid data, and each key's value is an object. The object contains information on what the data key's vaue should look like (what is its type, is it required, etc.)


### Discussion Questions
1. **What is one benefit of JavaScript not enforcing type?** It can be faster to learn for beginners.
2. **What is one downside of JavaScript not enforcing type?** It can be hard to track errors where a variable is not containing the type of data that it should.
3. **Should the parameters of a function be changed when the function returns? Why or why not?** I am a little fuzzy on what this question is asking. If it is asking if we should manipulate the inputs of a function, I think that depends on the situation. I would likely air toward _not_ manipulating the original data, so that it could be used elsewhere in its original fashion if needed.
4. **Describe a type of data that has rules, aside from the given examples of Number, Integer and Float. What are the rules the data should follow?** According to [javascript.info](https://javascript.info/types), the Number type cannot represent integer values larger than 2<sup>53</sup>, so `BigInt` is a type designed to represent integers or arbitrary length. It is created by appending `n` to the end of an integer literal.


[Back to Home](README.md)