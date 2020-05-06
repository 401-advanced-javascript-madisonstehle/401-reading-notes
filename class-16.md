# Class-16
## Event Driven Applications

### Links
- [Event Driven Programming](https://alligator.io/nodejs/event-driven-programming/)
- [Node Docs: Events](https://nodejs.org/api/events.html)
- [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- [Events and Event Emitter in Node.js](https://www.youtube.com/watch?v=l20MBBFZAmA)

### Discussion Questions
1. **Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?** Routing for information, async calls, auth/auth
2. **Why are events sometimes better than asynchronous actions with callbacks?** You can easily assign multiple listeners to an event, but having a lot of callbacks on one thing can get messy really fast.
3. **What does an EventEmitter instance do?** It is an exported class that allows us to raise new event s and to listen to events that have been raised.
4. **When is a program’s call stack, event queue, and event loop active?** Whenever the application is running and doing things, this process is running, with the application constantly checking if the call stack is empty.


#### [Back to Home](README.md)