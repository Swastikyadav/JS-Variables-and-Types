1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
<!-- name is the variable in which "Mark" (string) is stored. -->

2. Find the error if any
```js
  var product cost = 3.45;
```
<!-- The variable name is wrong. There should not be space between product and cost. Correct options are: product_cost or productCost -->

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" Right
  'Hello World" Wrong
  "Hello World' Wrong
  'Hello World' Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;      // Valid
var 1girl;    // Invalid - variable can't start with number.
var woman3;   // Valid
var -girl;    // Valid
var blackDog; // Valid - Camel Casing.
var 42;       // Invalid - variable can't start with number.
var $42;      // Valid - Cant start with special character.
var userName; // Valid - Camel Casing
var x, y, z;  // Valid - Can declare multiple variables in one line.
var x = 5, y = 6, z = 7; // Valid - Can assign valuew to multiple variables in one line.
var x = 5 + 10 + 2;      // Valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
let less_amount = amount - 2080;

// Define a new variable and store the value that is 200 more then the value of amount.
let more_amount = amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.
let times_amount = amount * 4;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
let remainder_amount = amount % 21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
johnAge > markAge // True, John is older

// Check who is younger
johnAge > markAge // True, Mark is younger

// Check if their age is equal
johnAge == markAge // False

// Create a new variable and assign the age of john to new variable.
let newAge = johnAge; 

// Check if john is equal to or greater then mark.
newAge >= markAge // True

// Check if john is less then or equal to mark.
newAge <= markAge // False

// Calculate the average age of john and mark and assign to a new variable.
let averageAge = (newAge + markAge) / 2;
```