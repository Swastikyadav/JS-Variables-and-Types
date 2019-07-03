1. 🎖 Write a program to calculate the total price of your phone purchase. With these conditions
 * [ ] You will keep purchasing phones (hint: loop!) until you run out of bank balance.
 * [ ] You'll also buy accessories for each phone as long as your purchase amount is below your spending threshold.
 * [ ] After you've calculated your purchase amount, add in the tax, then print out the calculated purchase amount, properly formatted.
 * [ ] Finally, check the amount against your bank account balance to see if you can afford it or not.
 * [ ] Write a function called calculateTax which takes an argument 'amount' and calculates the tax you need to pay.
 * [ ] Write a function named formatAmount which returns you amount in this format '$ 132.45' make the decimal fixed to 2 places.
```js
const SPENDING_THRESHOLD = 200;
const TAX_RATE = 0.08;
const PHONE_PRICE = 99.99;
const ACCESSORY_PRICE = 9.99;

var bank_balance = 303.91;
var amount = 0;
// your code goes here

while (true) {
	if (amount > bank_balance) break;
	amount += PHONE_PRICE;
	if (amount < SPENDING_THRESHOLD) {
		amount += ACCESSORY_PRICE;	
	}
}
function calculateTax(amount) {
    return amount * TAX_RATE;
}
var finalAmount = calculateTax(amount) + amount;
console.log(finalAmount.toFixed(2));
```
 ⛑ Answer of the above will `$334.76`.

2. 🎖 Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen using `alert` (e.g. "2 is even").
```js
// your code goes here

for (var i = 0; i <= 20; i++) {
    if (i % 2) {
        alert(`${i} is odd`);
    } else {
        alert(`${i} is even`);
    }
}
```

3. 🎖Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result in console (e.g. "2 * 9 = 18").

```js
// Your code goes here
for (var i = 0; i <= 10; i++) {
    console.log(i*9);
}
```

4. 🎖Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).
(e.g.
"1 * 1 = 1"
"1 * 2 = 2"
"1 * 3 = 3"
"1 * 4 = 4"
.... for all 100 results)

```js
// Your code goes here
for (var i = 1; i < 11; i++) {
    for (var j = 1; j < 11; j++) {
        let product = i*j;
        console.log(`${i} * ${j} = ${product}`);
    }
}
```

5. 🎖Show the following output using one loop.
```js
// 1, 2, 3, 4, 5
// 6, 7, 8, 9, 10

// Your code goes here
var line1 = "";
var line2 = "";
for (var i = 1; i < 11; i++) {
    if (i < 6) {line1 += i + " ";}
    else {line2 += i + " ";}
}
console.log(line1);
console.log(line2);
```

6. 🎖Use a while loop to add up the numbers 1 to 20.
```js
// Your code goes here
var total = 0;
var i = 0;
while (i < 21) {
    total = total + i;
    i++;
}
alert(total);
```

7. 🎖Use a while loop to print out the even number from 1 to 20. (You'll need Modulus for this. And an IF Statement.)
```js
// Your code goes here

var i = 0;
while(i < 21) {
    if (i%2 == 0) {
        console.log(i);
    }
    i++;
}
```
