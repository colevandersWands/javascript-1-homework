> complete the rest of [basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) on FCC and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 

## Counting Cards
[PYH](http://www.pythontutor.com/javascript.html#code=var%20count%20%3D%200%3B%0Afunction%20cc%28card%29%20%7B%0A%20%20//%20Only%20change%20code%20below%20this%20line%0A%20%20switch%28card%29%0A%20%20%7B%0A%20%20%20%20case%202%3A%0A%20%20%20%20case%203%3A%0A%20%20%20%20case%204%3A%0A%20%20%20%20case%205%3A%0A%20%20%20%20case%206%3A%0A%20%20%20%20count%2B%3D1%3B%0A%20%20%20%20break%3B%0A%20%20%20%20case%2010%3A%0A%20%20%20%20case%20'J'%3A%0A%20%20%20%20case%20'Q'%3A%0A%20%20%20%20case%20'K'%3A%0A%20%20%20%20case%20'A'%3A%0A%20%20%20%20count-%3D1%3B%0A%20%20%20%20break%3B%0A%20%20%7D%0A%20%20%20if%20%28count%20%3E%200%29%7B%0A%20%20%20%20%20return%20count%20%2B%20%22%20Bet%22%3B%0A%20%20%20%7D%20else%7B%0A%20%20%20%20%20return%20count%20%2B%20%22%20Hold%22%3B%0A%20%20%20%7D%0A%20%20//%20Only%20change%20code%20above%20this%20line%0A%7D%0A//%20Add/remove%20calls%20to%20test%20your%20function.%0A//%20Note%3A%20Only%20the%20last%20will%20display%0Acc%282%29%3B%20cc%283%29%3B%20cc%287%29%3B%20cc%28'K'%29%3B%20cc%28'A'%29%3B&curInstr=33&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
var count = 0;
function cc(card) {
  // Only change code below this line
  switch(card)
  {
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
    count+=1;
    break;
    case 10:
    case 'J':
    case 'Q':
    case 'K':
    case 'A':
    count-=1;
    break;
  }
   if (count > 0){
     return count + " Bet";
   } else{
     return count + " Hold";
   }
  // Only change code above this line
}
cc(2); cc(3); cc(7); cc('K'); cc('A');
```
##  Build JavaScript Objects
[PYH]()
```js
```
## Accessing Object Properties with Dot Notation
[PYH]()
```js
```
## Accessing Object Properties with Bracket Notation
[PYH]()
```js
```
## Accessing Object Properties with Variables
[PYH]()
```js
```
## Updating Object Properties
[PYH]()
```js
```
## Add New Properties to a JavaScript Object
[PYH]()
```js
```
## Delete Properties from a JavaScript Object
[PYH]()
```js
```
## Using Objects for Lookups
[PYH]()
```js
```
## Testing Objects for Properties
[PYH]()
```js
```
## Manipulating Complex Objects
[PYH]()
```js
```
## Accessing Nested Objects
[PYH]()
```js
```
## Accessing Nested Arrays
[PYH]()
```js
```
## Record Collection
[PYH]()
```js
```
## Iterate with JavaScript While Loops
[PYH]()
```js
```
## Iterate with JavaScript For Loops
[PYH]()
```js
```
## Iterate Odd Numbers With a For Loop
[PYH]()
```js
```
## Count Backwards With a For Loop
[PYH]()
```js
```
## Iterate Through an Array with a For Loop
[PYH]()
```js
```
## Nesting For Loops
[PYH]()
```js
```
## Iterate with JavaScript Do...While Loops
[PYH]()
```js
```
## Profile Lookup
[PYH]()
```js
```
## Generate Random Fractions with JavaScript
[PYH]()
```js
```
## Generate Random Whole Numbers with JavaScript
[PYH]()
```js
```
## Generate Random Whole Numbers within a Range
[PYH]()
```js
```
## Use the parseInt Function
[PYH]()
```js
```
## Use the parseInt Function with a Radix
[PYH]()
```js
```
## Use the Conditional (Ternary) Operator
[PYH]()
```js
```
## Use Multiple Conditional (Ternary) Operators
[PYH]()
```js
```
