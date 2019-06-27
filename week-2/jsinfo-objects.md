> start (and try to finish) the [object tasks](https://javascript.info/object) from javascript.info and paste each of your solutions into this file.    
> Don't be afraid of peeking at the solutions!  Just be sure you study them well

## 1. Hello, Object
```js
let user = {
  name: 'John',
  surname: 'Smith',
}
user.name = 'Pete';
delete user.name;
```
## 2. check for empytiness 
```js
function isEmpty(obj) {
  for (let key in obj) {
    return false;
  }
  return true;
}
```
## 3. Is it possible to change an object declared with const?
 yes.
## 4. Some Object Property
```js
let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130
}
let sum = 0;
for(let key in salaries){
let holder = salaries[key];
sum = holder + sum;
}
console.log(sum);
```
## 5. Multiply numeric properties by 2
```js
let menu = {
  width: 200,
  height: 300,
  title: "My menu"
};
function multiplyNumber(obj){
  for (let prop in obj){
if (typeof obj[prop] === Number){
    obj[prop] = obj[prop] * 2;
}
  }
    
}
console.log(multiplyNumber(menu));
```
