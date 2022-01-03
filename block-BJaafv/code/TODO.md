1. What is the difference between the two `sum` function given below?

````````js
// first
function sum(a, b) {
  return a + b;
}
sum(12,24,32)
``````It will return the sum of the parameter a and b.

// second
function sum(a, b) {
  console.log(a + b);
}
```````This will make the sum print in the console section.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Ans- If we store the returned of both function , the value would be total of sum .

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

Ans-When we shall call the sum function with three parameter it will take only parameter as many as we have declared in the function.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
Ans-yes, function can be stored in a variable.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

Ans-
```js
function sayHello(name){
  return (`Hello ${name}`)
}
sayHello(`Arya`)

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
``` Output will be `Hello, John`

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1  John

showMessage(); // Output 2  `Hello John`

alert(userName); // Output 3   John
````````

8. What is a Anonymous Function give example of three functions.
   Ans- When the function has no name , that kind of function called as Anonymous Function

````js
const  addNumber=function(numA,numB){
  return (numA+numB)
}
addNumber(5,5)

```js
const addNumber=(numA,numB)=>{
  return numA+numB;
}
addNumber(5,5)

```js
const square=(num)=>num*num;
square(5)

9. Can function declaration be a Anonymous Function? Explain
Ans- Function declaration can be a anonymous function ,Function declared is by function keyword but in anonymous  there is no need to defined function name.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
````

```js
function getAdd(a, b) {
  return a + b;
}

function calcExpression(a, b, c, d) {
  return (a * b(c - b)) / d;
}

function createHelloWorld(name) {
  return name;
}
function checkType(something){
  return typeof(something)
}
```
