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
## 80. Build JavaScript Objects 
```js
var myDog = {
  "name": "Boby",
  "legs": 4,
  "tails": 1,
  "friends": ["tom", "Jerry"] 
};
```
## 81. Accessing Object Properties with Dot Notation
```js
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};
var hatValue = testObj.hat;      // Change this line
var shirtValue = testObj.shirt; 
```
## 82. Accessing Object Properties with Bracket Notation
```js
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};
// Only change code below this line
var entreeValue = testObj['an entree'];   // Change this line
var drinkValue = testObj['the drink']; 
```
## 83. Accessing Object Properties with Variables
```js
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};
var playerNumber = 16;       // Change this Line
var player = testObj[playerNumber]; 
```
## 84. Updating Object Properties
```js
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
myDog['name'] = 'Happy Coder';
```
## 85. Add New Properties to a JavaScript Object
```js
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
myDog.bark = 'woof';
```
## 86. Delete Properties from a JavaScript Object
```js
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line.
delete myDog.tails;
````
## 87. Using Objects for Lookups
```js
function phoneticLookup(val) {
  var result = "";

  // Only change code below this line
  var lookup = {
    alpha: 'Adams',
    bravo: 'Boston',
    charlie : 'Chicago',
    delta: 'Denver',
    echo: 'Easy',
    foxtrot : 'Frank',
  };
  // Only change code above this line
  return result = lookup[val];
}
// Change this value to test
phoneticLookup("charlie");
````
## 88. Testing Objects for Properties
```js
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here
  if(myObj.hasOwnProperty(checkProp)){
    return myObj[checkProp];
  }else{
    return "Not Found";
  }  
}
// Test your code by modifying these values
checkObj("gift");
```

