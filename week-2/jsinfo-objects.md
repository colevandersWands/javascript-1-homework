> start (and try to finish) the [object tasks](https://javascript.info/object) from javascript.info and paste each of your solutions into this file.    
> Don't be afraid of peeking at the solutions!  Just be sure you study them well

## Hello, object
importance: 5
Write the code, one line for each action:

1. Create an empty object user.
2. Add the property name with the value John.
3. Add the property surname with the value Smith.
4. Change the value of the name to Pete.
5. Remove the property name from the object.

```js
```
## Check for emptiness
importance: 5
Write the function isEmpty(obj) which returns true if the object has no properties, false otherwise.

Should work like that:

```js
let schedule = {};
alert( isEmpty(schedule) ); // true
schedule["8:30"] = "get up";
alert( isEmpty(schedule) ); // false
```
## Constant objects?
importance: 5
Is it possible to change an object declared with const? What do you think?
```js
const user = {
  name: "John"
};
// does it work?
user.name = "Pete";
```

## Sum object properties
importance: 5
We have an object storing salaries of our team:
```js
let salaries = {
  John: 100,
  Ann: 160,
  Pete: 130
}
```
Write the code to sum all salaries and store in the variable sum. Should be 390 in the example above.
If salaries is empty, then the result must be 0.

## Multiply numeric properties by 2
importance: 3
Create a function multiplyNumeric(obj) that multiplies all numeric properties of obj by 2.
For instance:

```js
// before the call
let menu = {
  width: 200,
  height: 300,
  title: "My menu"
};
multiplyNumeric(menu);
// after the call
menu = {
  width: 400,
  height: 600,
  title: "My menu"
};
```
Please note that multiplyNumeric does not need to return anything. It should modify the object in-place.
P.S. Use typeof to check for a number here.
