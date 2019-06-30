1. 🎖 What's the outpit of the code below
```js
typeof "Joe"; // String
typeof 4;     // Number
typeof NaN;   // Number
typeof false; // Boolean
typeof function () {}; // Function
var phone = 8983700;   // Number
typeof phone; // Undefined 
typeof null;  // Null
```

2. 🎖 Output of the code below
```js
// Convert num into string
var num = 45;
String(num); // "45"
String(321); // "321"
String(300 + 23); // "323" 
String(false); // "false"
String(true);  // "true"
Number("3.18"); // 3.18
Number(" "); // 0
Number("");  // 0
Number("22 44"); // NaN
Number(false); // 0
Number(true); // 1
```

3. 🎖 Output of the following

```js
var x = 10 + "1"; 
console.log(x); // "101"
typeof x; // String
```