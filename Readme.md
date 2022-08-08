### General Technical
- What is Code Quality? How you asses the code quality? What makes a Quality Software?
- How are you going to design an authentication system? Http Only Cookie, Refresh Tokens.
- What’s the difference between SSE and SE? What makes SSE an SSE?

### Javascript
- Closures (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
- What are Promises? Please explain in a way that you’re explaining it to child.
- 
### React
- What’s your favourite feature in React?
- What is React to you? Why React? What’s the best thing of React? How react is more performant than other alternatives? (Diffing Algorithm and Reconciliation).
- Passing prop from parent to grand child (Prop Drilling)?
    - https://javascript.plainenglish.io/how-to-avoid-prop-drilling-in-react-using-component-composition-c42adfcdde1b
    - Context is primarily used when some data needs to be accessible by *many* components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.
    - **If you only want to avoid passing some props through many levels, [component composition](https://reactjs.org/docs/composition-vs-inheritance.html) is often a simpler solution than context.**
    - [https://reactjs.org/docs/composition-vs-inheritance.html](https://reactjs.org/docs/composition-vs-inheritance.html)
- What is diffing algorithm? How reconciliation works in React?
- Passing Data from Child to Parent?
- Composition vs Inheritance in React? 
    - https://reactjs.org/docs/composition-vs-inheritance.html
- What is the use of `Keys` in React? Why we can not use `index` as a Key in React?
- What the difference between Shallow Comparison and Deep Comparison?
    - [https://reactjs.org/docs/shallow-compare.html](https://reactjs.org/docs/shallow-compare.html)
    - [https://stackoverflow.com/questions/36084515/how-does-shallow-compare-work-in-react](https://stackoverflow.com/questions/36084515/how-does-shallow-compare-work-in-react)
- What are the different Life Cycle Methods you know? What are the alternatives of Life Cycle Methods in Functional Components?
    - [https://stackoverflow.com/questions/53464595/how-to-use-componentwillmount-in-react-hooks](https://stackoverflow.com/questions/53464595/how-to-use-componentwillmount-in-react-hooks)
    - [https://tsh.io/blog/react-component-lifecycle-methods-vs-hooks/](https://tsh.io/blog/react-component-lifecycle-methods-vs-hooks/)
    - [https://reactjs.org/docs/hooks-faq.html](https://reactjs.org/docs/hooks-faq.html)
- What's the difference between Component and PureComponent in React?
- How can one achieve shouldComponentUpdate like behaviour in React Functional Component?

### State Management
- What is Redux? What’s the benefits of it as compared to other state management solutions?

### Behavioural
- What if you deploy a service and in the middle of night, it breaks? What are you going to do? How you trigger company wide alerts?
