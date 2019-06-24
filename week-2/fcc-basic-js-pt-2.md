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
[PYH](http://www.pythontutor.com/javascript.html#code=var%20myDog%20%3D%20%7B%0A%20%20%22name%22%3A%20%22Olivier%22,%0A%20%20%22legs%22%3A%204,%0A%20%20%22tails%22%3A%201,%0A%20%20%22friends%22%3A%20%5B%22Almendra%22,%22Zeus%22,%22Coco%22,%22Luna%22,%22Bear%22,%22Rocky%22,%22Niebla%22%5D%0A%7D%3B%0A&curInstr=1&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
var myDog = {
  "name": "Olivier",
  "legs": 4,
  "tails": 1,
  "friends": ["Almendra","Zeus","Coco","Luna","Bear","Rocky","Niebla"]
};
```
## Accessing Object Properties with Dot Notation
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20testObj%20%3D%20%7B%0A%20%20%22hat%22%3A%20%22ballcap%22,%0A%20%20%22shirt%22%3A%20%22jersey%22,%0A%20%20%22shoes%22%3A%20%22cleats%22%0A%7D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line%0A%0Avar%20hatValue%20%3D%20testObj.hat%3B%20%20%20%20%20%20//%20Change%20this%20line%0Avar%20shirtValue%20%3D%20testObj.shirt%3B%20%20%20%20//%20Change%20this%20line&curInstr=3&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

// Only change code below this line
var hatValue = testObj.hat;      // Change this line
var shirtValue = testObj.shirt;    // Change this line
```
## Accessing Object Properties with Bracket Notation
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20testObj%20%3D%20%7B%0A%20%20%22an%20entree%22%3A%20%22hamburger%22,%0A%20%20%22my%20side%22%3A%20%22veggies%22,%0A%20%20%22the%20drink%22%3A%20%22water%22%0A%7D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line%0A%0Avar%20entreeValue%20%3D%20testObj%5B%22an%20entree%22%5D%3B%20%20%20//%20Change%20this%20line%0Avar%20drinkValue%20%3D%20testObj%5B%22the%20drink%22%5D%3B%20%20%20%20//%20Change%20this%20line&curInstr=3&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};
// Only change code below this line
var entreeValue = testObj["an entree"];   // Change this line
var drinkValue = testObj["the drink"];    // Change this line
```
## Accessing Object Properties with Variables
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20testObj%20%3D%20%7B%0A%20%2012%3A%20%22Namath%22,%0A%20%2016%3A%20%22Montana%22,%0A%20%2019%3A%20%22Unitas%22%0A%7D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line%3B%0A%0Avar%20playerNumber%3D16%3B%20%20%20%20%20%20%20//%20Change%20this%20Line%0Avar%20player%20%3D%20testObj%5BplayerNumber%5D%3B%20%20%20//%20Change%20this%20Line&curInstr=3&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line;

var playerNumber=16;       // Change this Line
var player = testObj[playerNumber];   // Change this Line
```
## Updating Object Properties
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myDog%20%3D%20%7B%0A%20%20%22name%22%3A%20%22Coder%22,%0A%20%20%22legs%22%3A%204,%0A%20%20%22tails%22%3A%201,%0A%20%20%22friends%22%3A%20%5B%22freeCodeCamp%20Campers%22%5D%0A%7D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0AmyDog.name%20%3D%20%22Happy%20Coder%22%3B%0A&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};
// Only change code below this line.
myDog.name = "Happy Coder";
```
## Add New Properties to a JavaScript Object
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myDog%20%3D%20%7B%0A%20%20%22name%22%3A%20%22Happy%20Coder%22,%0A%20%20%22legs%22%3A%204,%0A%20%20%22tails%22%3A%201,%0A%20%20%22friends%22%3A%20%5B%22freeCodeCamp%20Campers%22%5D%0A%7D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0AmyDog.bark%3D%22Gua%20Guau%22&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};
// Only change code below this line.
myDog.bark="Gua Guau"
```
## Delete Properties from a JavaScript Object
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myDog%20%3D%20%7B%0A%20%20%22name%22%3A%20%22Happy%20Coder%22,%0A%20%20%22legs%22%3A%204,%0A%20%20%22tails%22%3A%201,%0A%20%20%22friends%22%3A%20%5B%22freeCodeCamp%20Campers%22%5D,%0A%20%20%22bark%22%3A%20%22woof%22%0A%7D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0Adelete%20myDog.tails%3B%0A&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line.
delete myDog.tails;
```
## Using Objects for Lookups
[PYH](ttp://www.pythontutor.com/javascript.html#code=//%20Setup%0Afunction%20phoneticLookup%28val%29%20%7B%0A%20%20var%20result%20%3D%20%22%22%3B%0A%20%20//%20Only%20change%20code%20below%20this%20line%0A%0A%20%20var%20obj%20%3D%20%7B%0A%20%20%20%20%22alpha%22%3A%20%20%22Adams%22,%0A%20%20%20%20%22bravo%22%3A%20%20%22Boston%22,%0A%20%20%20%20%22charlie%22%3A%22Chicago%22,%0A%20%20%20%20%22delta%22%3A%20%20%22Denver%22,%0A%20%20%20%20%22echo%22%3A%20%20%20%22Easy%22,%0A%20%20%20%20%22foxtrot%22%3A%22Frank%22%0A%20%20%7D%0A%20%20result%3Dobj%5Bval%5D%3B%0A%20%20//%20Only%20change%20code%20above%20this%20line%0A%20%20return%20result%3B%0A%7D%0A%0A//%20Change%20this%20value%20to%20test%0AphoneticLookup%28%22charlie%22%29%3B&curInstr=5&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
function phoneticLookup(val) {
  var result = "";
  // Only change code below this line

  var obj = {
    "alpha":  "Adams",
    "bravo":  "Boston",
    "charlie":"Chicago",
    "delta":  "Denver",
    "echo":   "Easy",
    "foxtrot":"Frank"
  }
  result=obj[val];
  // Only change code above this line
  return result;
}

// Change this value to test
phoneticLookup("charlie");
```
## Testing Objects for Properties
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myObj%20%3D%20%7B%0A%20%20gift%3A%20%22pony%22,%0A%20%20pet%3A%20%22kitten%22,%0A%20%20bed%3A%20%22sleigh%22%0A%7D%3B%0A%0Afunction%20checkObj%28checkProp%29%20%7B%0A%20%20//%20Your%20Code%20Here%0A%20%20if%28myObj.hasOwnProperty%28checkProp%29%29%0A%20%20%20%20return%20myObj%5BcheckProp%5D%3B%0A%20%20else%0A%20%20%20%20%20return%20%22Not%20Found%22%3B%0A%7D%0A%0A//%20Test%20your%20code%20by%20modifying%20these%20values%0AcheckObj%28%22gift%22%29%3B&curInstr=5&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};
function checkObj(checkProp) {
  // Your Code Here
  if(myObj.hasOwnProperty(checkProp))
    return myObj[checkProp];
  else
     return "Not Found";
}
// Test your code by modifying these values
checkObj("gift");
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
