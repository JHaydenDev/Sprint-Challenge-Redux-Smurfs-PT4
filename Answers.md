1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects? Which method do we use to create a new object while extending the properties of another object?

.map() .filter() (...) spread operator.
The spread operator usually is the method used to create a new object while exstending the properties of another object.

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions are objects or functions which feed into the reducer and describe a change to state. The reducer contains the logic behind the action that modifies state. The store is the overall state container an is "the single source of truth."

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?

Application state is global state while Component state is localized to a component.

1.  What is middleware?

A third party exstention point between dispatching a action and the store.

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

Redux thunk is middleware that allows asynchronous functions to be run.

1.  Which `react-redux` method links up our `components` with our `redux store`?

connect()()


