1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total)  => {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function percentage (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
}
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Ans-Function definition is an expression in JavaScript because an expression is anything that results into a value.
```js
let add = function (a, b) {
  return a + b;
};
```
4. Why is a function call an expression in JavaScript?
Ans- Function call is an expression in JavaScript because its outcome is an value.
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}
// These ans are based on if we do this in diferent console but if we do it in the same one then five = five(10,11); is valid.
let five = add(2, 3); // valid
five = add; // not valid as the end result will not come
five = five(10, 11); // not valid as five is not defined.
five = function () {
  return 'Hello';
}; // invalid as it is totally unrelated to the above function.
```

6. What is the difference between function definition and function call? Explain with an example.
Ans- Function defination means that function is giving steps that will follow when ever it is called and function call is when we execute it or call it so the function can take it steps.
7. What is the similarities between function definition and function call?
Ans- They both are an object and can be declared as an value of a variable.
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid as we are manifesting a variable named user will a value of sam.
```

9. What is higher order function explain with an example.
Ans: A function that accepts a function definition as an argument is known as Higher order function.
10. Explain what is callback function. Why you can pass a function inside a function?
