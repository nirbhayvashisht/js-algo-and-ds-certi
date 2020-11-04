<h1 align=center>freeCodeCamp JavaScript Algorithms and Data Structures Certification</h1>

# Basic JavaScript

## Types of variables
undefined, null, boolean, string, symbol, bigint, number and object

# ES6

## Destructuring
```JavaScript
const user = { name: 'John Doe', age: 34 };

const name = user.name; // name = 'John Doe'
const age = user.age; // age = 34
//can be written as

const { name, age } = user;
// name = 'John Doe', age = 34

//Here's how you can give new variable names in the assignment:

const { name: userName, age: userAge } = user;
// userName = 'John Doe', userAge = 34

const user = {
  johnDoe: { 
    age: 34,
    email: 'johnDoe@freeCodeCamp.com'
  }
};
//Here's how to extract the values of object properties and assign them to variables with the same name:

const { johnDoe: { age, email }} = user;
//And here's how you can assign an object properties' values to variables with different names:

const { johnDoe: { age: userAge, email: userEmail }} = user;
```

