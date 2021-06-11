1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```

in first one,we can store the value in any variable but in second one it,s only show value in console. 2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
ans:the value is same. 3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
ans:output is 26,the function have only two parameter to read. 4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
ans.yes,we can because function have return statement. 5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
ans:function sayHello(name){
return `Hello ${name}`;
} 6. What will be the output of the function below and why?

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

showMessage();
```

ans:Hello, John 7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

alert(userName); // John

showMessage(); // Hello, John

alert(userName); // Output 3//John
```

8. What is a Anonymous Function give example of three functions.
   ans:const add = function(a,b){
   return a+b;
   }
   const sub = function(a,b){
   return a-b;
   }
   const mul = function(a,b){
   return a\*b;
   }
9. Can function declaration be a Anonymous Function? Explain
   ans:yes,we can use declaration function as an anonymous function,we have to use return in that function.
10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.
ans:add,mul,sub,reverseToString,getData.
It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.
ans:show_message,add_number.
For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
