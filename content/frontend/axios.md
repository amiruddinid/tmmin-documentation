
---
part: NextBook
title: Getting Started
---
# What is Axios ?

Axios is a _[promise-based](https://javascript.info/promise-basics)_ HTTP Client for [`node.js`](https://nodejs.org/) and the browser. It is _[isomorphic](https://www.lullabot.com/articles/what-is-an-isomorphic-application)_ (= it can run in the browser and nodejs with the same codebase). On the server-side it uses the native node.js `http` module, while on the client (browser) it uses XMLHttpRequests.

# Why Axios?

Axios is a popular JavaScript library used for making HTTP requests from both the browser and Node.js environments. Below are key reasons why developers often choose Axios for their projects:

#### 1. **Easy to Use**

- Axios provides a simple and intuitive API for making HTTP requests. It is easy to get started with, allowing you to perform common operations like `GET`, `POST`, `PUT`, `DELETE`, and more, with minimal code. It also supports Promises, making asynchronous handling straightforward with `.then()` and `.catch()` methods or `async/await` syntax.

#### 2. **Request and Response Interceptors**

- Axios supports interceptors, which allow you to modify requests or responses before they are handled by `then` or `catch`. This is particularly useful for adding authorization tokens to requests or handling errors globally. Interceptors can be set up to act on every request or response, helping centralize code for authentication, logging, and error handling.

#### 3. **Support for All HTTP Request Methods**

- Axios supports all the major HTTP methods such as `GET`, `POST`, `PUT`, `PATCH`, and `DELETE`. It can easily handle different content types and allows for efficient data transmission, including JSON, form data, or URL-encoded data. This versatility makes it a great choice for both simple and complex API interactions.

#### 4. **Request Cancellation**

- Axios allows you to cancel requests that are no longer needed, which is especially useful for improving performance in situations where requests become irrelevant (e.g., when navigating to another page or selecting a different option). You can cancel requests by using Axios's built-in cancellation token.

#### 5. **Automatic JSON Parsing**

- Axios automatically parses JSON responses into JavaScript objects, reducing the need for manual parsing. This is a time-saver and ensures that you don't need to manually handle data transformations in every request.

#### 6. **Flexible Configuration**

- Axios provides extensive options for request configuration. You can customize headers, set timeouts, and configure other parameters like response types or base URLs globally. This flexibility allows you to tailor your requests to the specific needs of your application.

#### 7. **Parallel Requests**

- Axios allows you to perform multiple HTTP requests in parallel. Using `axios.all()` and `axios.spread()`, you can send several requests simultaneously and handle their responses together, improving the efficiency of your application.

#### 8. **Works in Both Browser and Node.js**

- Axios is designed to be used both in the browser and in Node.js environments, making it a versatile choice for full-stack developers. This enables a seamless experience when working on client-side or server-side applications.

#### 9. **Support for File Uploads**

- Axios provides support for sending `multipart/form-data`, which is typically used for uploading files or sending form data. This feature is essential when building applications that require file handling, such as image uploads or form submissions.

#### 10. **Asynchronous Programming**

- Axios integrates smoothly with `async/await`, which allows you to write asynchronous code in a more readable and structured manner. This simplifies the management of complex workflows involving multiple HTTP requests.

#### 11. **Lightweight**

- Despite being feature-rich, Axios remains lightweight and does not introduce heavy dependencies, making it a good choice for developers who want a balance between functionality and performance.

### Conclusion

Axios is widely used because of its ease of use, flexibility, and rich feature set. It simplifies the process of making HTTP requests, especially in modern web development. Its support for promises, request/response interception, automatic JSON parsing, and many other features make it a solid choice for developers working on both client-side and server-side applications.
