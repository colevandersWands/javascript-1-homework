> begin [the basic data structure exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-data-structures) and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
## 1. Use an Array to Store a Collection of Data
```js
let yourArray = [ 'this', 'is', 1, true, 'array'];
```
## 2. Access an Array's Contents Using Bracket Notation
```js
let myArray = ["a", "b", "c", "d"];
// change code below this line
 myArray[1] = 'second alphabet';
//change code above this line
console.log(myArray);
```
## 3. Add Items to an Array with push() and unshift()
```js
function mixedNumbers(arr) {
  // change code below this line
arr.unshift('I', 2, 'three');
arr.push(7, 'VIII', 9);
  // change code above this line
  return arr;
}
// do not change code below this line
console.log(mixedNumbers(['IV', 5, 'six']));
```
## 4. Remove Items from an Array with pop() and shift()
```js
function popShift(arr) {
  let popped = arr.pop(); // change this line
  let shifted = arr.shift(); // change this line
  return [shifted, popped];
}

// do not change code below this line
console.log(popShift(['challenge', 'is', 'not', 'complete']));
```
## 5. Remove Items Using splice()
```js
function sumOfTen(arr) {
  // change code below this line
  arr.splice(1,2);
  // change code above this line
  return arr.reduce((a, b) => a + b);
}
// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1]));
```
## 6. Add Items Using splice()
```js
function htmlColorNames(arr) {
  // change code below this line
  arr.splice(0,2,'DarkSalmon','BlanchedAlmond')
  // change code above this line
  return arr;
} 
 
// do not change code below this line
console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush', 'PaleTurqoise', 'FireBrick']));
```
## 7. Copy Array Items Using slice()
```js
function forecast(arr) {
  // change code below this line
  var newArry = arr.slice(2,4);
  return newArry;
}
// do not change code below this line
console.log(forecast(['cold', 'rainy', 'warm', 'sunny', 'cool', 'thunderstorms']));
```
## 8. Copy an Array with the Spread Operator
```js


