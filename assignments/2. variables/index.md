1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark"; //name is a variable name;
```

2. Find the error if any
```js
  var product cost = 3.45; // There can't be space in variable name
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" // Right
  'Hello World" // Wrong
  "Hello World' //Wrong
  'Hello World' // Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; // VALID
var 1girl; // INVALID
var woman3; // VALID
var -girl; // INVALID
var blackDog; // VALID
var 42; // INVALID
var $42; // VALID
var userName; // VALID
var x, y, z; // VALID
var x = 5, y = 6, z = 7; // VALID
var x = 5 + 10 + 2; // VALID
```

## Basic Operations

Mathematical Operations:

```js
var amount = 2080;
// Mathematical Operations:
// Define a new variable and store the value that is 80 less then the value of amount.
var newAmount1 = amount - 80;
// Define a new variable and store the value that is 200 more then the value of amount.
var newAmount2 = amount + 200;
// Define a new variable and store the value that is 4 times the value of amount.
var newAmount3 = amount * 4; 
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var newAmount4 = amount / 21;
```
Logical Operation
```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if(johnAge>markAge){
  console.log("John is older than Mark");
}else{
  console.log("Mark is older than John");
}
// Check who is younger
if(markAge>johnAge){
  console.log("John is younger than Mark");
}else{
  console.log("Mark is younger than John");
}
// Check if their age is equal
if(johnAge==markAge){
  console.log("Their age is equal");
}else{
  console.log("Their age is not equal");
}
// Create a new variable and assign the age of john to new variable.
var age = johnAge;
// Check if john is equal to or greater then mark.
if(johnAge>=markAge){
  console.log("John's age is equal to or greater than Mark's age")
}else{
  console.log("John's age is neither equal to nor greater than Mark's age")
}
// Check if john is less then or equal to mark.
if(johnAge<=markAge){
  console.log("John's age is neitherlesser than or equal to Mark's age.")
}else{
  console.log("John's age is neither lesser than nor equal to Mark's age.")
}
// Calculate the average age of john and mark and assign to a new variable.
var avgAge = (johnAge+markAge)/2;
```