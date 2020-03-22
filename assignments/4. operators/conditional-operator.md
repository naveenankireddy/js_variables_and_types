## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
```js
let numA = prompt('please enter a number');
let numB = prompt('please enter a number');
let operator = prompt('please enter an operator symbol');
if(operator == '+'){
  alert(numA + numB)
} else if(operator == '-'){
  if(numA < numB){
    alert('first num will be greater');
  }else{
    alert(numA - numB);
  }
}else if(operator == '*'){
alert(numA * numB);
}else if(operator == '/'){
  if(numA < numB){
    alert('first num will be greater');
  }else{
    alert(numA / numB);
  }
};
```


2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
if(status == 'single'){
  console.log(`${firstName} is single`);
}else{
  console.log(`${firstName} is married`);
}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
let numA = prompt('enter a number');
let numB = prompt('enter a number');
if(numA > numB){
  alert(numA);
}else{
  alert(numB)
};

```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
let numA = prompt('enter a number');
let numB = prompt('enter a number');
let numC = prompt('enter a number');
let product = numA * numB * numC;
if(product > 0){
  alert('positive +')
}else{
  alert('negative')
};
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
let number = prompt('enter a number')
switch(number){
  case '1':
    alert('one');
    break;
    case '2':
      alert('two');
      break;
      case '3':
    alert('three');
    break;
    case '4':
      alert('four');
      break;
      case '5':
    alert('five');
    break;
    case '6':
      alert('six');
      break;
      case '7':
      alert('seven');
      break;
      case '8':
    alert('eight');
    break;
    case '9':
      alert('nine');
      break;
  default('what wrong with you');

}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
let marks = prompt('enter your marks');
switch(marks){
  case marks > 90:
    alert('AA');
    break;
    case marks > 80 && marks<= 90:
      alert('AB');
      break;
      case marks > 70 && marks<= 80:
      alert('BB');
      break;
      case marks > 60 && marks<= 70:
      alert('BC');
      break;
      case marks > 50 && marks<= 60:
      alert('CC');
      break;
      case marks > 40 && marks<= 50:
      alert('CD');
      break;
      case marks > 30 && marks<= 40:
      alert('DD');
      break;
      case marks <= 30:
      alert('FF');
      break;

  
}
```
