1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";//name is a variable name;
```



2. Find the error if any

```js
  var product cost = 3.45;//cost is the error we can not give a space between variable name;
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" 
  //right
  'Hello World" 
  //wrong
  "Hello World' 
  //wrong
  'Hello World' 
  //right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;   //valid
var 1girl; //invalid y because we cant use number at starting of a varable name;
var woman3; //valid
var -girl; //invalid
var blackDog; //valid
var 42;//invalid
var $42; //valid
var userName; //valid
var x, y, z; // valid
var x = 5, y = 6, z = 7;  //valid
var x = 5 + 10 + 2; //valid
var user = "Tyrion"; "Arya"; "John"; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var substraction = amount - 80;
console.log(substraction);

// Define a new variable and store the value that is 200 more then the value of amount.
var addition = amount + 200;
console.log(addition);

// Define a new variable and store the value that is 4 times the value of amount.
var multiplication = amount * 4;
console.log(multiplication);

// Define a new variable and store the reminder when the value of amount is  divided by 21.
let division = amount % 21;
console.log(division);
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"
user = 'sam'
// Define a variable with name user with value "Irfan"
var user = 'Irfan' 

let number = 21;
// Reassign the value of number to 60
number = 60;
// Define another variable called number with the value of 100
let number = 100; // it is an error 

const username = "Admin";
// Reassign the value of username to "Arya"
username = 'arya';//we cannot reassign in constant  
// Define a variable called username with value "John"
const username = "Admin" // it is an error 
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
let older = (johnAge > markAge) ? "john is older" : "mark is older";
console.log(older);
// Check who is younger
let younger = (johnAge < markAge) ? "john is younger" : "mark is younger";
console.log(younger);
// Check if their age is equal
console.log(johnAge == markAge)
// Create a new variable and assign the age of john to new variable.
let naveenAge = johnAge;
// Check if john is equal to or greater then mark.
console.log(johnAge >= markAge);
// Check if john is less then or equal to mark.
console.log(johnAge <= markAge);

// Calculate the average age of john and mark and assign to a new variable.
let average = johnAge + markAge / 2;
console.log(average);
```
