> [FCC basic algorithm scripting](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-algorithm-scripting) - complete a few and paste your solutions into this MD file.  
> recommended challenges (alphabetically): celcius to farenheit, chunkey monkey, factorialize, falsey bouncer, largest of 4, repeat, reverse a string, title case.  And the rest are also great
> examples to study: [samanthaming](https://github.com/samanthaming/freecodecamp-my-solutions/tree/master/basic-algorithm), [jadonOrr](https://github.com/jadonOrr/freeCodeCampAlgorithms/tree/master/basic-algorithms), [TheNewStyles](https://github.com/TheNewStyles/freecodecamp-algorithm-solutions/tree/master/BasicAlgorithmScripting)

## 1. Convert Celsius to Fahrenheit
```js
function convertToF(celsius) {
  let fahrenheit;
  fahrenheit = celsius * 9/5 + 32;
  return fahrenheit;
}

convertToF(30);
```
## 2. Reverse a String
```js
function reverseString(str) {
let arr = str.split('');
let arr2 = [];
for(let i = str.length-1  ; i >= 0; i--){
arr2.push(arr[i]);
}
let _str = arr2.join("");
return _str;
}
reverseString("hello");
```
## 3. Factorialize a Number
```js
function factorialize(num) {
let product = 1;
for (let i = num; i > 1; i--){
product = product * i ;
}
return product; 
}
factorialize(5);
```
## 4. Find the Longest Word in a String
```js 
function findLongestWordLength(str) {
  let arr = str.split(' ');
  let maximum = 0;
  for (let i = 0; i < arr.length ; i++){
  if(arr[i].length > maximum){
  maximum = arr[i].length;
   }
  }
  return maximum;
}

findLongestWordLength("The quick brown fox jumped over the lazy dog");
```
## 5. Return Largest Numbers in Arrays
```js
function largestOfFour(arr) {
  // You can do this!
  let newArray = [];
  for(let i = 0 ; i < arr.length ; i++){
  let maxnum = -Infinity;  
  for(let j = 0; j < arr[i].length; j++){
    if(arr[i][j] > maxnum){
      maxnum = arr[i][j];
      }      
    }
  newArray.push(maxnum);
    }  
return newArray;
}

largestOfFour([[4, 5, 1, 3], [13, 27, 18, 26], [32, 35, 37, 39], [1000, 1001, 857, 1]]);
```
## 6. Confirm the Ending
```js
function confirmEnding(str, target) {
  // "Never give up and good luck will find you."
  // -- Falcor
  return str.slice(-target.length) === target;
}

confirmEnding("Bastian", "n");
```
## 7.  Repeat a String Repeat a String
```js
function repeatStringNumTimes(str, num) {
  // repeat after me
  let answer = '';
  for (let i = 1; i <= num; i++){
  answer = str + answer;
  }
  return answer;
}

let a = repeatStringNumTimes("abc", 3);
```
## 8. Truncate a String
```js
function truncateString(str, num) {
  // Clear out that junk in your trunk
  let sliced = str.slice(0, num);
  if(num >= str.length){
  return sliced;
  }else {
      return `${sliced}...`;   
  }
}

truncateString("A-tisket a-tasket A green and yellow basket", 8);
```
## 9. Finders Keepers
```js
function findElement(arr, func) {
 let num = 0;
 for (let i = 0; i < arr.length; i++){
  num = arr[i];
  if (func(num)){
    return num;
    }
    }  
    return undefined;
}

findElement([1, 2, 3, 4], num => num % 2 === 0);
```
## 10. Boo who
```js
function booWho(bool) {
  // What is the new fad diet for ghost developers? The Boolean.
let b = typeof bool;
if ( b === "boolean"){
  return true;
  } else {
    return false;
    }
}

let a = booWho([1, 2, 3]);
```
## 11. Title Case a Sentence
```js
function titleCase(str) {
 let words = str.toLowerCase().split(' ');
 for (let i = 0;  i < words.length ; i++){
 words[i] = words[i][0].toUpperCase() + words[i].slice(1);
   }
  return words.join(' '); 
}

let a = titleCase("I'm a little tea pot");
```
## 12. Slice and Splice
```js
function frankenSplice(arr1, arr2, n) {
  // It's alive. It's alive!
  let Arry = arr2.slice();
  for(let i = 0 ; i < arr1.length; i++){
    Arry.splice(n, 0, arr1[i]);
    n++
    }
  return Arry;
}

let a = frankenSplice([1, 2, 3], [4, 5, 6], 1);
```
## 13. Falsy Bouncer
```js





