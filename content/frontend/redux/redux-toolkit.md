---
part: NextBook
title: Getting Started
---
# What is Redux Toolkit ?

**Redux Toolkit** is an official, recommended library for managing state in Redux applications. It simplifies Redux usage by providing a set of utilities that streamline the process of creating actions, reducers, and store configurations. It helps reduce the amount of boilerplate code needed to implement Redux and promotes best practices for using Redux in modern applications.

Redux Toolkit was created to address some of the common issues developers face when working with Redux, such as complex setup, redundant code, and managing immutability in reducers. It aims to make Redux development faster and more efficient.

# Why Use Redux Toolkit ?

There are several key reasons why Redux Toolkit is beneficial:

1. **Simplified Setup**: Redux Toolkit provides a `configureStore` function that automatically sets up the Redux store with useful defaults, like middleware for handling asynchronous actions (e.g., `redux-thunk`).
2. **Reduced Boilerplate**: Redux Toolkit provides utilities like `createSlice` for simplifying action and reducer creation. This reduces the need for manually writing action types and action creators, which can be verbose and error-prone in traditional Redux.
3. **Immutable State Management**: Redux Toolkit uses the `Immer` library internally, which allows you to write "mutating" code in reducers while keeping the state immutable. This makes working with Redux reducers much easier and more intuitive.
4. **Built-in DevTools Support**: Redux Toolkit includes built-in support for Redux DevTools, making it easy to debug your application and inspect the Redux state and actions.
5. **Best Practices**: It encourages best practices by automatically setting up necessary middleware, enabling Redux DevTools, and enforcing modern Redux patterns like "slices" and "thunks" for handling asynchronous actions.
6. **Optimized for Efficiency**: With tools like `createAsyncThunk`, Redux Toolkit provides a cleaner and more powerful way to handle asynchronous actions, reducing the need to manage loading, success, and error states manually.

---

### Conclusion:

**Redux Toolkit** simplifies the process of using Redux by reducing boilerplate code and promoting modern best practices. It enhances the developer experience by making the setup and usage of Redux easier, while also providing tools to manage asynchronous logic, immutability, and state management in a more efficient way. By using Redux Toolkit, developers can build Redux-based applications faster, with less effort, and fewer chances for error, making it the go-to solution for state management in modern React applications.
