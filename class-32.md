# Class-32
## Redux - Asynchronous Actions

### Links
- [Dan Abramov on Suspense](https://www.youtube.com/watch?v=6g3g0Q_XVb4) (video)
- [Async Actions](https://redux.js.org/advanced/async-actions)
- [Thunk Middleware](https://github.com/reduxjs/redux-thunk)
- [Redux Actions using Redux Thunk](https://alligator.io/redux/redux-thunk/)
- [React Suspense (alpha/beta)](https://blog.logrocket.com/async-rendering-in-react-with-suspense-5d0eaac886c8/)


### Discussion
When you need your actions to do some asyncronous action before you dispatch it to the reducer, the setup of the action returns a function and _not an object_. The problem with this is that Redux doesn't want a function, it expects and requires an object.

This is where **"thunk"** comes in! Thunk is a middleware that ensures an object is returned. It inspects the dispatched actions and lets it through OR processes the function and then dispatches what the function returns.

We could potentially write something that does this, but the Thunk module is more stable and it provides error checking for us!


#### [Back to Home](README.md)