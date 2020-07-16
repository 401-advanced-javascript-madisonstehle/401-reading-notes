# Class-31
## Redux - Combined Reducers

### Links
- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)


### Discussion

> Combined Reducers is nothing more than pulling in more than one reducer from source and creating a keyed object from them.

`combineReducers` is imported from `'redux'` in your code, along with the normal `createStore`. You can create multiple reducers that keep track of different things, like users or tweets. Then, by using `combineReducers`, you can create an object for your reducers, with all your reducers as key/value pairs. You can `createStore` using the combined reducers object.

```js
const reducers = combineReducers({
  user: userReducer,
  tweets: tweetsReducer,
});

const store = createStore(reducers);
```

Doing this allows us to better organize our code, allowing for the Single Responsibility Principle to be implemented. Each reducer should have only one part of state to manage.



#### [Back to Home](README.md)