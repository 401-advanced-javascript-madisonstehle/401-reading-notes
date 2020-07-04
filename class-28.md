# Class-28
## Context API

### Links
- [Context API](https://reactjs.org/docs/context.html)
- [Hooks and Context Example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [React Context Links](https://github.com/diegohaz/awesome-react-context)

### Discussion Questions
1. **What is the difference between the variables `MyContext` and `MyProvider` in the examples above?** `MyProvider` is a class comoponent and `MyContext` is a context object and creates the provider behavior.
2. **Why is context useful?** Context acts as a kindOf Global. It can be used to give access to state variables throughout multiple nested components.
3. **Can a component outside of a provider get its context?** It's meant for chains of parent-childs props. If you want it outside of the provider, then you would need to have a context for that.


#### [Back to Home](README.md)