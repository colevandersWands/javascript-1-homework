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
## 5. 
