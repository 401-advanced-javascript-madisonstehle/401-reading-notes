# Class-24
## Component Composition

### Links
- [React Basics Recap](https://www.freecodecamp.org/news/these-are-the-concepts-you-should-know-in-react-js-after-you-learn-the-basics-ee1d2f4b8030/)
- [props.children](https://codeburst.io/a-quick-intro-to-reacts-props-children-cb3d2fce4891)
- [React Browser Router Tutorial](https://blog.pshrmn.com/simple-react-router-v4-tutorial/)
- [Composition vs. Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)
- [Browser Router API Docs](https://reacttraining.com/react-router/web/api)


### Discussion Questions
1. **Why do we not need more .html pages in a multi-page React app?** Because, with the `react-router-dom`, we will be able to render components on a page based on the browser URL!

2. **If we wanted a component to show up on every page, where would we put it and why?**
  - **Outside the `<BrowserRouter/>`**
  - **Inside the `<BrowserRouter />`, outside a `<Route />`**
  - **Inside a `<Route />`**

    I would guess that it would definitely need to be outside of a `<Route />`, The question is whether it would go inside the `<BrowserRouter />` or not. I think that it would go inside, so that it renders for each route.

3. **What does props.children contain?** It, in short, allows us to access the children of a tag by auto populating the key when a comoponent has content between the opening and closing tags.


#### [Back to Home](README.md)