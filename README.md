# Sending HTTP Requests/Connecting to a DB

This project is the https requests/connecting to a DB section from [React - The Complete Guide (incl Hooks, React Router, Redux)](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)

This app uses the [Star Wars API](https://swapi.dev/)

## Key Concepts

- API: Application Programming Interface
- JavaScript code should never reveal secure details of an app and should never directly communicate with a database
- async/await is just syntactic sugar to make `.then()` chains for promises look nicer in the code
  - Use try/catch for fetch if using async/await
- with function keyword, no problem using a function before it is defined because of hoisting, but with `const`, the function must be defined before it can be used
