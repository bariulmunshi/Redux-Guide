#  Table of Contents
  
- [step up Redux environment](#step-up-redux-environment )
- [Introduction to the course](#introduction-to-the-course )
- [Why do we need redux ?](#why-do-we-need-redux )
- [Inner working of redux.](#inner-working-of-redux )
- [slice](#slice )
  
#  step up Redux environment
  
1. import redux store: import { configureStore } from "@reduxjs/toolkit"; /_ import redux redux-step-1_/
2. connect app with redux store: <Provider store={store}>{/_ connect to the redux store with app redux-step-2_/} <App /> </Provider>
3. create slice within redux store: Import slice from redux-toolkit:import { createSlice } from "@reduxjs/toolkit";
4. connect state with component:
5. take input with dispatch & import action: 
  
#  Basic Question & Answer
  
  
- Redux Toolkit simplifies the Redux setup process, while Redux Thunk provides a middleware for handling asynchronous actions.Combined, they offer a powerful solution for state management in your React applications, following the principles of the BLoC architecture.
- What's Immer:behind the scenes ensure the immutable state management
  
#  Introduction to the course
  
  
##  what's need to learn this course
  
  
###  RTK means Redux Toolkit
  
  
- Redux Toolkit is used for writing redux code but in a more concise way
- Libraries of Redux: Redux Toolkit is updated version of React-Redux
  
###  RTK query
  
  
- RTK Query is a powerful data fetching and caching tool. It is designed to simplify common cases for loading data in a web application
- RTK query is part of Redux Toolkit
  
##  What's Redux?
  
  
- Redux is an open-source JavaScript library for managing and centralizing application state.
- Predictable,Centralized, Debuggable, Flexible
- Redux made by react engineer
- There are many state management libraries like Redux
  
##  Redux may use in different libraries including JavaScript
  
  
- As it a JavaScript library that's why we can use it in different libraries(vue.js, angular.js, etc)
- Redux is an open-source JavaScript library for managing and centralizing application state.
  
#  Why do we need redux?
  
  
- For manage state globally so that we can do task from central state
  
#  Inner working of redux.
  
  
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
  
  
##  slice
  
- A slice is the portion of Redux code that relates to a specific set of data and actions within the store's state.
Three part for create a slice
(name: 'counter', `kon slice er jonno kaj ta hocce seita porichoy korai dewa`
  initialState,
  reducers:)
- slice is individual business logic of every feature
- create slice & here counter folder is a individual slice
```sh
step 1: create features folder within redux & create counter folder within features folder
step 2: create counterSlice.js file within counter folder 
step 3: Now import the slice into counterSlice.js file
```
  