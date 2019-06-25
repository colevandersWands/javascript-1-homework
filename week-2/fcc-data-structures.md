> begin [the basic data structure exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-data-structures) and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  

## Use an Array to Store a Collection of Data
```js
let yourArray = [1,true,"hello","mame", null];
```
## Access an Array's Contents Using Bracket Notation
```js
let myArray = ["a", "b", "c", "d"];
// change code below this line
myArray[1]="n";
//change code above this line
console.log(myArray);
```
## Add Items to an Array with push() and unshift()
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
## Remove Items from an Array with pop() and shift()
```js
function popShift(arr) {
  let popped= arr.pop(); // change this line
  let shifted = arr.shift(); // change this line
   return [shifted, popped];
}
// do not change code below this line
console.log(popShift(['challenge', 'is', 'not', 'complete']));
```
## Remove Items Using splice()
```js
function sumOfTen(arr) {
  // change code below this line
  arr.splice(0, 1);
  arr.splice(1, 1);
  arr.splice(2, 2); 
  // change code above this line
  return arr.reduce((a, b) => a + b);
}
// do not change code below this line
console.log(sumOfTen([2, 5, 1, 5, 2, 1]));
```
## Add Items Using splice()
```js
function htmlColorNames(arr) {
  // change code below this line
  arr.splice(0,1,'DarkSalmon');
  arr.splice(1,1,'BlanchedAlmond');
  // change code above this line
  return arr;
} 
// do not change code below this line
console.log(htmlColorNames(['DarkGoldenRod', 'WhiteSmoke', 'LavenderBlush', 'PaleTurqoise', 'FireBrick']));
```
## Copy Array Items Using slice()
```js
function forecast(arr) {
  // change code below this line
 return  arr.slice(2,4);
}
// do not change code below this line
console.log(forecast(['cold', 'rainy', 'warm', 'sunny', 'cool', 'thunderstorms']));
```
## Copy an Array with the Spread Operator
```js
function copyMachine(arr, num) {
  let newArr = [];
  while (num >= 1) {
    // change code below this line
  newArr = [[...arr],...newArr];
    // change code above this line
    num--;
  }
  return newArr;
}
// change code here to test different cases:
console.log(copyMachine([true, false, true], 2));
```
## Combine Arrays with the Spread Operator
```js
```
## Check For The Presence of an Element With indexOf()
```js
```
## Iterate Through All an Array's Items Using For Loops
```js
```
## Create complex multi-dimensional arrays
```js
```
## Add Key-Value Pairs to JavaScript Objects
```js
```
## Modify an Object Nested Within an Object
```js
```
## Access Property Names with Bracket Notation
```js
```
## Use the delete Keyword to Remove Object Properties
```js
```
## Check if an Object has a Property
```js
```
## Iterate Through the Keys of an Object with a for...in Statement
```js
```
## Generate an Array of All Object Keys with Object.keys()
```js
```
## Modify an Array Stored in an Object
```js
```
