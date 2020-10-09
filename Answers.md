1. What problem does the context API help solve?

It helps contain pieces of state and pass it between your components without having to explicitly pass props to keep them all in synch.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

The store is a centralized place for us to store the state for our entire application, It is able to change state by calling a certain action that will dispatch an action that will line up in the reducer, where it will check what piece of state to change according to the action type that was passed.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

Application state is global while component state is local; You would want to use application state with pieces of state that needs to be passed to a lot of components so that you avoid neeeding to pass the state as props to every component that would need it.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
   redux thunk is a middleware that lets you call action creators that return a whole function instead of just an action object.

1. What is your favorite state management system you've learned and this sprint? Please explain why!
   Context API, just because of how easy it is to implement.
