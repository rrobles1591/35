### Conceptual Exercise

Answer the following questions below:

- What are some ways of managing asynchronous code in JavaScript?
then/catch method chaining and async/await

- What is a Promise?

A Promise is an object representing the eventual completion or failure of an asynchronous operation. 

- What are the differences between an async function and a regular function?

async returns a promise

- What is the difference between Node.js and Express.js?

NodeJS is a javascript runtime environment for running JavaScript programs and is used to build server-side applications. ExpressJS is a web framework that enables you to design a web application to handle a variety of different HTTP demands.

- What is the error-first callback pattern?

it's a function that returns an error object whenever any successful data is returned by the function

- What is middleware?

 its a function that will have all the access for requesting an object, responding to an object, and moving to the next middleware function in the application request-response cycle.

- What does the `next` function do?

- What are some issues with the following code? (consider all aspects: performance, structure, naming, etc)

```js
async function getUsers() {
  const elie = await $.getJSON('https://api.github.com/users/elie');
  const joel = await $.getJSON('https://api.github.com/users/joelburton');
  const matt = await $.getJSON('https://api.github.com/users/mmmaaatttttt');

  return [elie, matt, joel];
}
```

No response
