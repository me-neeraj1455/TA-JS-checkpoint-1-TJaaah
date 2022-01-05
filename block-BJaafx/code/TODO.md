1. Using loops take 10 inputs from user and find the average of all the numbers.

````js

let totalNum = 0;
for (let i = 1; i <= 10; i++) {
  totalNum = totalNum + Number(prompt(`Enter a ${i} number`));
}
let ave = totalNum / 10;
console.log(`Average is ${ave}`);


2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```// Uncaught ReferenceError: println is not defined


3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js

function getEvenSum(max = 10) {
  let total = 0;
  for (let i = 0; i <= max; i++) {
    if (i % 2 === 0) {
      total = total + i;
    }
  }
  return total;
}
getEvenSum(20);

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js

function getOddSum(max = 10) {
  let total = 0;
  for (let i = 0; i <= max; i++) {
    if (i % 2 !== 0) {
      total = total + i;
    }
  }
  return total;
}
getOddSum(5);

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.
```js



- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

let num = prompt(`Enter a number`);
function getProductOfDigits(num) {
  if (Number(num) < 0) {
    console.log(`not a valid input`);
  } else {
    let product = 1;
    for (let i = 0; i < num.length; i++) {

      product = product * Number(num[i]);
    }
    return product;
  }
}
getProductOfDigits(num);



6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // Bigger than 5'because num is grater than 5
check(1); // 'Smaller than 5'because num is less than 5
check(5); // 5, because 5 is neither less than 5 nor grater than 5
````

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") return "You are arya";
  if (name === "John") return "You are john";
  return "Who are you";
}

getOutput("Arya"); // "You are arya"--name is equal to Arya that is a string.
getOutput("John"); // "You are john" name is equal to John that is a string.
getOutput(); // "Who are you" ==This time we don't provide any argument at time of calling the function that is why it returns `Who are you`.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") console.log("You are arya");
  if (name === "John") console.log("You are john");
  return "Who are you";
}

getOutput("Arya"); // `You are arya`--`Who are you` It will return always who are you in this function because it is outside of the if condition.
getOutput("John"); // `You are John`--who  are you
getOutput(); // `Who are you`
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

````js
A function can have multiple return statement according to its condition .

function even(num){
  if(num%2===0){
    return (`${num} is even`)
  }else{
    return (`${num} is odd`)
  }
}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

```js
The difference between for loop and while loop is that in for loop the number of iterations to be done is already known and is used to obtain a certain result whereas in while loop the command runs until a certain condition is reached and the statement is proved to be false.

 for(let i =0;i<=10;i++){

 }
````

let num=prompt(`Enter a number`)
while(i<=num){

}
