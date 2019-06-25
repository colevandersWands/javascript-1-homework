> start (and try to finish) the [loop tasks](https://javascript.info/while-for) from javascript.info and paste each of your solutions into this file.  
> Don't be afraid of peeking at the solutions!  Just be sure you study them well

## Last loop value  
What is the last value alerted by this code? Why?
```js
let i = 3;

while (i) {
  alert( i-- );
}
```
#### Answer:\ The last value is i=1, because  the While condition is 0 and 0 means false in boolean value. 


## Which values does the while loop show?
The prefix form ++i:
```js
let i = 0;
while (++i < 5) alert( i );
```

#### Answer:\ The first value is i=1,the the first while condition is "1<5" and first alert is i=1, because  i++ means add 1 before the evaluation. The next values for i=2,i=3,i=4 will have the same behavior. And finally evaluation is 5<5, the alert was printed in 4 times. 

The postfix form i++
```js
let i = 0;
while (i++ < 5) alert( i );
```
#### Answer:\ The first value is i=1,the the first while condition is "0<5" and first alert is i=0, because  +++ means add 1 after the evaluation. The next values for i=2,i=3,i=4,i=5 will have the same behavior. And finally evaluation is 5<5, the alert was printed in 5 times.

## Which values get shown by the "for" loop?

The prefix form ++i:
```js
for (let i = 0; i < 5; i++) alert( i );
```
#### Answer:\ The first value is i=0,the the first fot condition is "0<5", first alert is i=0 and adding 1 to i value. The next values for i=2,i=3,i=4 will have the same behavior. And finally evaluation is 5<5, the alert was printed in 5 times.


The postfix form i++
```js
for (let i = 0; i < 5; ++i) alert( i );
```
#### Answer:\ The first value is i = 0, the first "for" condition is "0 <5", first alert is i = 0 and adding 1 to i value. The next values for i=1, i = 2, i = 3, i = 4 will have the same behavior. And finally evaluation is 5 <5, the alert was printed in 5 times. In both (i++ and ++i ) cases the result is the same because the increment is made in the end of "for" iteration.


## Output even numbers in the loop

Use the for loop to output even numbers from 2 to 10.

```js
for (let i = 2; i < 11; i+=2) alert( i );
```

##  Replace "for" with "while"
Rewrite the code changing the for loop to while without altering its behavior (the output should stay same).
```js
let i=0;
 while (i < 3) {
   alert( `number ${i}!` );
   i++
 }
```
##  Repeat until the input is correct
```js
  <script>
      let number;
  do {
      bnumber = prompt("Please enter a number less than 100",0);
     }while(number>=100)
  </script>
```

##  Output prime numbers
```js
var n = 25;
for (var i= 2; i < n ; i++){
  var prime= true;
    for (var j =2; j<i; j++){
        if (i%j== 0){
        prime = false; 
        break;
        }
    }
   if (prime) alert( i ); 
}
 
```
