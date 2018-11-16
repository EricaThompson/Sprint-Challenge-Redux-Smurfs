1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?
- .filter(), .map(), .find()

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
- actions: "payloads of information that send data from your application to your store"
- https://redux.js.org/basics/actions
- reducers: "a pure function that takes the previous state and an action, and returns the next state. It's called a reducer because it's the type of function you would pass to Array.prototype.reduce(reducer, ?initialValue)." 
- https://redux.js.org/basics/reducers
- store: "a state container for JavaScript apps"
- https://medium.com/the-web-tub/managing-your-react-state-with-redux-affab72de4b1

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?
- "..application state is global, and your component state is local."
-https://teamtreehouse.com/community/what-is-the-difference-between-application-state-and-component-state-in-react
- Application state when sharing between multiple components, component for things within a singular scope

1.  What is middleware?
- Acts in between two different functionalities to be able to extend abilities further

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
- "It is middleware allows you to write action creators that return a function instead of an action."
- It enables use of actionCreaters in addition to action (object)

1.  Which `react-redux` method links up our `components` with our `redux store`?
- connect()
