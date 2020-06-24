# Class-26
## Hooks API

### Links
- [Making Sense of React Hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)
- [Using the State Hook](https://reactjs.org/docs/hooks-state.html)
- [Hooks at a Glance](https://reactjs.org/docs/hooks-overview.html)
- [Hooks API Reference](https://reactjs.org/docs/hooks-reference.html)
- [Using the Effect Hook](https://reactjs.org/docs/hooks-effect.html)


### Discussion Questions
1. **What does a component’s lifecycle refer to?** They are functions that are automatically called by React when a class component renders, mounts, changes, unmounts, and more.
2. **Why are functional components preferred over class components?** They're much easier to implement.
3. **What is wrong with the following code?**
```js
import React, {useState, useEffect} from 'react'; 
   
function MyComponent(props) {
  const [count, setCount] = useState(0); 
     
  function changeCount(e) {
    setCount(e.target.value); 
  }
     
  let renderedItems = []
     
  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update'); 
    }, [count]); 
       
    renderedItems.push(<div key={i}>Item</div>); 
  }
     
  return (<div>
    	<input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```
The renderedItems and for loops aren't in a function.



#### [Back to Home](README.md)