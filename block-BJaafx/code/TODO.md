1. Using loops take 10 inputs from user and find the average of all the numbers.
   function takeTenNumber(){
   let value = 0;
   for(let i=1; i<=10;i++){
   let sum =+prompt("enter a number");
   value +=sum;
   }
   return value;
   }
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println("hi");
  i++;
}
```

ans:error,println is not defined. 3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
function getEvenSum(max = 10){
let value=0;
for(let i=1;i<=max;i++){
if(i % 2=== 0){
value +=i;
}
}
return value;
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
   function getOddSum(max = 10){
   let value=0;
   for(let i=2;i<=max;i++){
   if(i % 2!== 0){
   value +=i;
   }
   }
   return value;
   }
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
  ans:function getProductOfDigits(num){
  if(num<0){
  return "not a valid input";
  }else{
  let product =1;
  while(num > 0){
  product = num % 10;
  num = Math.floor(num /10);
  if(num >= 10){
  product _= num % 10;
  }else{
  product _= num/10;
  }
  return product;
  }
  }
  }

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return "Bigger than 5";
  }

  if (num < 5) {
    return "Smaller than 5";
  }

  return num;
}

check(10); // "Bigger than 5"
check(1); // "smaller than 5"
check(5); // 5;
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") return "You are arya";
  if (name === "John") return "You are john";
  return "Who are you";
}

getOutput("Arya"); // "you are arya";
getOutput("John"); // "you are john";
getOutput(); // "who are you";
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") console.log("You are arya");
  if (name === "John") console.log("You are john");
  return "Who are you";
}

getOutput("Arya"); // "you are arya";"who are you"
getOutput("John"); // "you are john";"who are you"
getOutput(); // "who are you"
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
   ans:function do not have multiple statement return statement but while using switch or if condition we can use multiple return statement.
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
    ans:for loop use,when know the value of iteration and in while loop we don't know the value of iteration.
