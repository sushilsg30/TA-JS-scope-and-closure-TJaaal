1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
}; 
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression. // Beacuse function is object.

let addNumber = (num1,num2) => {
  return num1 + num2;
}

4. Why is a function call an expression in JavaScript? // function is object we call is within a function as argument. It always return a value.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
} 

let five = add(2, 3); // valid 5
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example. // function definition define whole function call is lower order function call just as argument.

function add(){

}
add(); //call


7. What is the similarities between function definition and function call? // both declared function difference only in usecase.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.// which take function call
// accept function definition

10. Explain what is callback function. Why you can pass a function inside a function? // function we use in HOF, function is object.
