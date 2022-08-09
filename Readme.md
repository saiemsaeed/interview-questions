### General Technical
- What is Code Quality? How you asses the code quality? What makes a Quality Software?
- How are you going to design an authentication system? Http Only Cookie, Refresh Tokens.
- What’s the difference between SSE and SE? What makes SSE an SSE?
- How we we achieve communication between different browser tabs?
- What happens when you hit a url from your browser? How an HTTP request works?
- How caching works in the browser? How you can cache a file in browser? What different cache eviction policies you know?
- What is different between Hasing and Encryption?
- What is difference between Authorization and Authentication?
- What is Memoization?
    - Memoization is an optimisation technique used to primarily speed up programs by storing the results of expensive function calls and returning the cached results when the same inputs occur again.
    - [https://medium.com/geekculture/memoization-in-react-native-ca894819ccff](https://medium.com/geekculture/memoization-in-react-native-ca894819ccff)
    - [https://www.qed42.com/insights/coe/javascript/optimize-your-react-app-performance-memoization](https://www.qed42.com/insights/coe/javascript/optimize-your-react-app-performance-memoization)
- Link Prefetching
    - [https://developer.mozilla.org/en-US/docs/Web/HTTP/Link_prefetching_FAQ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Link_prefetching_FAQ)
    - [https://www.igvita.com/2015/08/17/eliminating-roundtrips-with-preconnect/](https://www.igvita.com/2015/08/17/eliminating-roundtrips-with-preconnect/)
    - [https://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers/#section:dns-prefetching](https://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers/#section:dns-prefetching)
    - [https://css-tricks.com/prefetching-preloading-prebrowsing/](https://css-tricks.com/prefetching-preloading-prebrowsing/)

### Javascript
- Closures (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
- What are Promises? What's the benefit of using Promises? Please explain in a way that you’re explaining it to child.
- Hoisting (https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
- Events in Javascript. How Event Delegation and Event Bubbling works? (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- Difference between Array.forEach and Array.map function?
- What is Set in Javascript? What the usecase of Set?
- Does array destructuring gives shallow copy or deep copy variables?
- How to make a copy of an array or object? 
    - Using Spread Operators
- What are different primitve data types in Javascript?
- What are different Scopes in Javascript? (https://dmitripavlutin.com/javascript-scope/)
- What's the difference between var, let and const?
- Difference between double (==) and triple equals (===)? Which one is faster and why?
- What do you know about Prototypal Inheritance? Is it different from Class based inheritance?
- How can we run promises sequentially?
- What's the difference between `||` and `??`?
- What is Symbol primitive type? What is the benefit of using it?


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
- How can we check types in React without Typescript?
    - [https://reactjs.org/docs/typechecking-with-proptypes.html](https://reactjs.org/docs/typechecking-with-proptypes.html)
    - [https://reactjs.org/docs/static-type-checking.html](https://reactjs.org/docs/static-type-checking.html)
- What are React Hooks? Why we need them? Why we can't put React Hooks inside conditional blocks (if)?
    - [https://usehooks.com/](https://usehooks.com/)
    - [https://reactjs.org/docs/hooks-intro.html](https://reactjs.org/docs/hooks-intro.html)
- How rendering works in React? What is the functionality of ReactDOM.render function?
    - Render function for ReactDOM.render is responsible for kicking off the reconciliation process. So it does the generate the virtual dom, generate tree of elements and actually insert it into the dom. React dom does not come from React library, and the reason for this is that React job is to just do the diffing, it doesn't actually know that you are generating dom. React and ReactDom used to come in one bundle back before v13. React is compatible for any dom insertion tool. Whole point of React is diffing thing, so you (being developer) don't have to thing about it.
    - [https://www.simform.com/react-performance/](https://www.simform.com/react-performance/)
    - [https://jelvix.com/blog/is-react-js-fast](https://jelvix.com/blog/is-react-js-fast)
    - [https://medium.com/@thinkwik/why-reactjs-is-gaining-so-much-popularity-these-days-c3aa686ec0b3](https://medium.com/@thinkwik/why-reactjs-is-gaining-so-much-popularity-these-days-c3aa686ec0b3)
    - [https://www.stefankrause.net/js-frameworks-benchmark5/webdriver-ts/table.html](https://www.stefankrause.net/js-frameworks-benchmark5/webdriver-ts/table.html)
    - [https://reactjs.org/docs/reconciliation.html#recursing-on-children](https://reactjs.org/docs/reconciliation.html#recursing-on-children)
- `useMemo` vs `useCallback`. How they are same? and How they are different?
    - https://kentcdodds.com/blog/usememo-and-usecallback
- What do you know about `useEffect`? How is the different from `useLayoutEffect`?
    - https://epicreact.dev/myths-about-useeffect/
    - https://kentcdodds.com/blog/useeffect-vs-uselayouteffect    

### State Management
- What is Redux? What’s the benefits of it as compared to other state management solutions?
- Difference between Flux and Redux?
    - https://stackoverflow.com/questions/32461229/why-use-redux-over-facebook-flux

### Behavioural
- What if you deploy a service and in the middle of night, it breaks? What are you going to do? How you trigger company wide alerts?
- Imagine you had a low performer on your team. How would you handle the situation? What would you do to help them?
- Describe a time when there was a conflict within your team. How did you help resolve the conflict? Did you do anything to prevent it in the future?
- Why do you want to work at <company-name>?
- Describe a time when you strongly disagreed with a coworker about an engineering decision. How did you go about making the final decision? What did you do after the decision was made?
- Imagine you and your team are in the middle of a major project at work, with many moving parts, complicated context, a lot of work, etc.. A new software engineer joins your team, and you're tasked with onboarding them; what do you do?
- How would you go about distributing work for a project across a team of software engineers? If you've led a project in the past, describe what you did.
- Describe a time when you made a mistake. How did you deal with the repercussions of the mistake? What lessons did you learn from the mistake?
- Describe a challenging project that you worked on. Why was it challenging? What was your role in the project? How did you deal with the various difficulties of the project?
- Describe a time when you went out of your comfort zone. Why did you do it? What lessons did you learn from the experience?
