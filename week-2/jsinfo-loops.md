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

#### Answer:\ The first value is i=1,the the first while condition is "1<5" and first alert is i=1, because  i++ means add 1 before the evaluation. The next values for i=2,i=3,i=4 will have the same behavior. And finally evaluatio is 5<5, the alert was printed in 4 times. 

The postfix form i++
```js
let i = 0;
while (i++ < 5) alert( i );
```
#### Answer:\ The first value is i=1,the the first while condition is "0<5" and first alert is i=0, because  +++ means add 1 after the evaluation. The next values for i=2,i=3,i=4,i=5 will have the same behavior. And finally evaluatio is 5<5, the alert was printed in 5 times.
