> complete the rest of [basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) on FCC and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 
[Completed Excersise from 1 -78](https://github.com/Berihugebre/javascript-1-homework/blob/master/week-1/fcc-basic-js-pt-1.md) 
## 79. Counting Cards
```js 
var count = 0;

function cc(card) {
  // Only change code below this line
  switch(card){
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
    count = count + 1;
    break;
    case 7:
    case 8:
    case 9:
    count = count + 0;
    break;
    case 10:
    case 'J':
    case 'Q':
    case 'K':
    case 'A':
    count = count - 1;
    break;
  }
  if (count > 0){
    return count + ' Bet';
  }else 
  return count + " Hold";
  // Only change code above this line
}

// Add/remove calls to test your function.
// Note: Only the last will display
cc(2); cc(3); cc(7); cc('K'); cc('A');
```
