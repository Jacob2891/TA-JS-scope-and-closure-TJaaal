1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage = function  (marks, total) {
  return (marks * 100) / total
}

let percentage =(marks, total) => {
  return (marks * 100) / total
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let pct = (marks , total) => {
return (marks * 100) / total
};
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

function percentage (marks, total) {
return (marks*100) / total
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let pct = (marks,total) => {
  return (marks * 100) / total
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

(marks,total) => {
  return (marks * 100) / total
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;

function percentage (marks,total) {
  return (marks * 100) / total
};
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Reason:

function defination is an expression becasue a function resolves to a value , which happens to be defination of an expression .

Code:

```js
function multiply (num1 , num2) {
return (num1 * num2);
};
```

4. Why is a function call an expression in JavaScript?

function is an expression becasue a function resolves to a value , which happens to be defination of an expression .

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid
five = add; // Valid
five = five(10, 11); // Invalid . five isnt defined
five = function () {
  return 'Hello';
}; // Valid , Anonymous function.
```

6. What is the difference between function definition and function call? Explain with an example.

Function Definition : we declare a function here

```js
function add (a,b) {
return (a+b)
};
```

Function Call : we refer to a previously declared funtion and then call it later by adding () to the function reference

```js
add(3,5);
```
7. What is the similarities between function definition and function call?

parameter and argument are a link in this case , arguments ib function call takes values from the parameters defined by us in function definition

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid , as the user will be added along with its value
```

9. What is higher order function explain with an example.

Higher order function is a function where we use a function as a parameter or return a function.

ex:- 

```js
function doOperation (operation,num1,num2) {
return operation(num1,num2)
};
```

```js
function add (a, b) {
  return a+b
}
```
10. Explain what is callback function. Why you can pass a function inside a function?

Callback function is a function which is passed inside another function , we can pass a function as callback becase function is an object.
