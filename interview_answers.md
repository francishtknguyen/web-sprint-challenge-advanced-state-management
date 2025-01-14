# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

Copntext API solves the problem of prop drilling through components that don't use the props and instead allows you to skip that component and provide props to the grandchild componeent directly.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

action types and creators define what type of action to take when entering a new state, reducers are the brains behind mutating a copy of the state data, the store is the all truth with the initial state data that is used to be mutated when state data changes.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

It allows us to to use async logic to interact with our store. This changes our action creators by allowing us to create an action for each async action, which makes it easier to debug our code when running to errors.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

Redux is my favorite because the ability to pass state data anywhere in our program anytime and the ability to mutate the data without disruptign the store data.