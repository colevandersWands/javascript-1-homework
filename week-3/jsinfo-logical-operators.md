> start (and try to finish) the [loop tasks](https://javascript.info/logical-operators) from javascript.info and paste each of your solutions into this file.  
> things that might help: [truthiness](https://github.com/janke-learning/truthiness/blob/master/README.md)

## 1. What is the output?
1. ```alert( null || 2 || undefined );```
 solution
The answer is 2, that’s the first truthy value.
2.``` alert( alert(1) || 2 || alert(3) );```
solution
The answer: first 1, then 2.
3. ```alert( 1 && null && 2 );```
solution
The answer: null, because it’s the first falsy value from the list.
4. ```alert( alert(1) && alert(2) );```
solution
The answer: 1, and then undefined.
5. ```alert( null || 2 && 3 || 4 );```
solution
The answer: 3.
6. Write an “if” condition to check that age is between 14 and 90 inclusively.
“Inclusively” means that age can reach the edges 14 or 90.

solution
```if (age >= 14 && age <= 90)```
7. Write an if condition to check that age is NOT between 14 and 90 inclusively.
Create two variants: the first one using NOT !, the second one – without it.

solution
The first variant:
```if (!(age >= 14 && age <= 90))```

The second variant:
```if (age < 14 || age > 90)```
8. Which of these alerts are going to execute?
What will the results of the expressions be inside if(...)?
```js
if (-1 || 0) alert( 'first' );
if (-1 && 0) alert( 'second' );
if (null || -1 && 1) alert( 'third' );
```
solution
The answer: the _*first*_ and the _third_ will execute.
