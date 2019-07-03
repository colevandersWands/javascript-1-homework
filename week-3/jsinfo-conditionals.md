> start (and try to finish) the [conditional tasks](https://javascript.info/ifelse) from javascript.info and paste each of your solutions into this file.  
> things that might help: [javascript.inf - comparisons](https://javascript.info/comparison), [interactive coercion table](https://janke-learning.org/equalities-coercion/), [equalities table](https://dorey.github.io/JavaScript-Equality-Table/)

### 1. if (a string with zero)
Will alert be shown?
```js
if ("0") {
  alert( 'Hello' );
}
```
solution
Yes, it will.

Any string except an empty one (and "0" is not empty) becomes true in the logical context.
### 2. The name of JavaScript
Using the if..else construct, write the code which asks: ‘What is the “official” name of JavaScript?’

If the visitor enters “ECMAScript”, then output “Right!”, otherwise – output: “Didn’t know? ECMAScript!”
```js
let JsName = prompt('What is te offical name of Javascript','');
if(JsName == 'ECMAScript'){
alert ('Right');
}
else {
alert ('Didn’t know? ECMAScript!');
}
```
### 3. Show the sign
Using if..else, write the code which gets a number via prompt and then shows in alert:

1, if the value is greater than zero,
-1, if less than zero,
0, if equals zero.
```js
{
let showssign = prompt('Enter any number','');
if(showssign > 0){
alert ('1');
}
else if(showssign < 0){
alert ('-1');
} else {
alert (0);
}
}
```
### 4. Rewrite 'if' into '?'

Rewrite this if using the ternary operator '?':
```js
if (a + b < 4) {
  result = 'Below';
} else {
  result = 'Over';
}
```
solution 

```js result = (a + b < 4) ? 'Below' : 'Over'; ```
### 5. Rewrite 'if..else' into '?'
Rewrite if..else using multiple ternary operators '?'.
For readability, it’s recommended to split the code into multiple lines.
let message;
```js
if (login == 'Employee') {
  message = 'Hello';
} else if (login == 'Director') {
  message = 'Greetings';
} else if (login == '') {
  message = 'No login';
} else {
  message = '';
}
```
solution
```js
let message = (login == 'Employee') ? 'Hello' :
  (login == 'Director') ? 'Greetings' :
  (login == '') ? 'No login' :
  '';
  ```
