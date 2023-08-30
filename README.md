# Table of Contents
- [Introduction to the course](#introduction-to-the-course)
- [Why do we need redux ?](#why-do-we-need-redux)
- [Inner working of redux.](#inner-working-of-redux)



# Introduction to the course
## What's Redux?
- Redux is an open-source JavaScript library for managing and centralizing application state.
- Predictable,Centralized, Debuggable, Flexible
- Redux made by react engineer
- There are many state management libraries like Redux

## Redux may use in different libraries including JavaScript
- As it a JavaScript library that's why we can use it in different libraries(vue.js, angular.js, etc) 
- Redux is an open-source JavaScript library for managing and centralizing application state.

## RTK means Redux Toolkit 
- Redux Toolkit is used for writing redux code but in a more concise way
- Libraries of Redux: Redux Toolkit is updated version of React-Redux

## RTK query    
- RTK Query is a powerful data fetching and caching tool. It is designed to simplify common cases for loading data in a web application
- RTK query is part of Redux Toolkit

# Why do we need redux?
- For manage state globally so that we can do task from central state

# Inner working of redux.
- 5 core concepts of redux which is correlated with each other
- `Action `
  - Each `action `take by user. Each `action` has a corresponding `reducer function.`
- `Dispatch `
  - Sending the `action` to the store. `Dispatching` an action triggers the corresponding `reducer` update the state.
- `Payload`
  - optional data that's attached to an `action`. It carries any additional information that needs to be sent along with the `action` to update the `state.`
- `Reducer`
  - A `reducer is a pure function` that takes the current state and an action as inputs and returns a new state. It defines how the application's state changes in response to different actions.
- `Store`
  - The `store` holds the state of the application. The `store` is responsible for dispatching actions, maintaining the state, and notifying subscribers about the state changes.