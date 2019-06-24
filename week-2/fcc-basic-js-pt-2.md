> complete the rest of [basic JS exercises](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript) on FCC and paste each of your solutions into this file.  This will allow you to use your FCC exercises as a study reference later on  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/freecode_camp_solutions.MD) 


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
[PYH](http://www.pythontutor.com/javascript.html#code=var%20myMusic%20%3D%20%5B%0A%20%20%7B%0A%20%20%20%20%22artist%22%3A%20%22Billy%20Joel%22,%0A%20%20%20%20%22title%22%3A%20%22Piano%20Man%22,%0A%20%20%20%20%22release_year%22%3A%201973,%0A%20%20%20%20%22formats%22%3A%20%5B%20%0A%20%20%20%20%20%20%22CD%22,%0A%20%20%20%20%20%20%228T%22,%0A%20%20%20%20%20%20%22LP%22%0A%20%20%20%20%5D,%0A%20%20%20%20%22gold%22%3A%20true%0A%20%20%7D%0A%20%20//%20Add%20record%20here%0A%20%20,%7B%0A%20%20%20%20%22artist%22%3A%20%22Guns%20N'%20Roses%22,%0A%20%20%20%20%22title%22%3A%20%22Use%20Your%20Illusion%20I%22,%0A%20%20%20%20%22release_year%22%3A%201991,%0A%20%20%20%20%22formats%22%3A%20%5B%20%0A%20%20%20%20%20%20%22CD%22,%0A%20%20%20%20%20%20%22Cassette%20Tape%22%0A%20%20%20%20%5D,%0A%20%20%20%20%22gold%22%3A%20true%0A%20%20%7D%0A%0A%0A%5D%3B&curInstr=1&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  }
  // Add record here
  ,{
    "artist": "Guns N' Roses",
    "title": "Use Your Illusion I",
    "release_year": 1991,
    "formats": [ 
      "CD",
      "Cassette Tape"
    ],
    "gold": true
  }
];
```
## Accessing Nested Objects
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myStorage%20%3D%20%7B%0A%20%20%22car%22%3A%20%7B%0A%20%20%20%20%22inside%22%3A%20%7B%0A%20%20%20%20%20%20%22glove%20box%22%3A%20%22maps%22,%0A%20%20%20%20%20%20%22passenger%20seat%22%3A%20%22crumbs%22%0A%20%20%20%20%20%7D,%0A%20%20%20%20%22outside%22%3A%20%7B%0A%20%20%20%20%20%20%22trunk%22%3A%20%22jack%22%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%3B%0Avar%20gloveBoxContents%20%3D%20%20myStorage.car.inside%5B%22glove%20box%22%5D%3B%20//%20Change%20this%20line%0A&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};
var gloveBoxContents =  myStorage.car.inside["glove box"]; // Change this line
```
## Accessing Nested Arrays
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myPlants%20%3D%20%5B%0A%20%20%7B%20%0A%20%20%20%20type%3A%20%22flowers%22,%0A%20%20%20%20list%3A%20%5B%0A%20%20%20%20%20%20%22rose%22,%0A%20%20%20%20%20%20%22tulip%22,%0A%20%20%20%20%20%20%22dandelion%22%0A%20%20%20%20%5D%0A%20%20%7D,%0A%20%20%7B%0A%20%20%20%20type%3A%20%22trees%22,%0A%20%20%20%20list%3A%20%5B%0A%20%20%20%20%20%20%22fir%22,%0A%20%20%20%20%20%20%22pine%22,%0A%20%20%20%20%20%20%22birch%22%0A%20%20%20%20%5D%0A%20%20%7D%20%20%0A%5D%3B%0A//%20Only%20change%20code%20below%20this%20line%0Avar%20secondTree%20%3D%20myPlants%5B1%5D.list%5B1%5D%3B%20//%20Change%20this%20line%0A&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];
// Only change code below this line
var secondTree = myPlants[1].list[1]; // Change this line
```
## Record Collection
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20collection%20%3D%20%7B%0A%20%20%20%20%222548%22%3A%20%7B%0A%20%20%20%20%20%20%22album%22%3A%20%22Slippery%20When%20Wet%22,%0A%20%20%20%20%20%20%22artist%22%3A%20%22Bon%20Jovi%22,%0A%20%20%20%20%20%20%22tracks%22%3A%20%5B%20%0A%20%20%20%20%20%20%20%20%22Let%20It%20Rock%22,%20%0A%20%20%20%20%20%20%20%20%22You%20Give%20Love%20a%20Bad%20Name%22%20%0A%20%20%20%20%20%20%5D%0A%20%20%20%20%7D,%0A%20%20%20%20%222468%22%3A%20%7B%0A%20%20%20%20%20%20%22album%22%3A%20%221999%22,%0A%20%20%20%20%20%20%22artist%22%3A%20%22Prince%22,%0A%20%20%20%20%20%20%22tracks%22%3A%20%5B%20%0A%20%20%20%20%20%20%20%20%221999%22,%20%0A%20%20%20%20%20%20%20%20%22Little%20Red%20Corvette%22%20%0A%20%20%20%20%20%20%5D%0A%20%20%20%20%7D,%0A%20%20%20%20%221245%22%3A%20%7B%0A%20%20%20%20%20%20%22artist%22%3A%20%22Robert%20Palmer%22,%0A%20%20%20%20%20%20%22tracks%22%3A%20%5B%20%5D%0A%20%20%20%20%7D,%0A%20%20%20%20%225439%22%3A%20%7B%0A%20%20%20%20%20%20%22album%22%3A%20%22ABBA%20Gold%22%0A%20%20%20%20%7D%0A%7D%3B%0A//%20Keep%20a%20copy%20of%20the%20collection%20for%20tests%0Avar%20collectionCopy%20%3D%20JSON.parse%28JSON.stringify%28collection%29%29%3B%0A//%20Only%20change%20code%20below%20this%20line%0Afunction%20updateRecords%28id,%20prop,%20value%29%20%7B%0A%20%20if%20%28!%28value%3D%3D%22%22%20%26%26collectionCopy%5Bid%5D.hasOwnProperty%28prop%29%20%29%29%7B%0A%20%20%20%20switch%28prop%29%7B%0A%20%20%20%20%20case%20%22album%22%3A%0A%20%20%20%20%20case%20%22artist%22%3A%0A%20%20%20%20%20%20%20%20%20%20collectionCopy%5Bid%5D%5Bprop%5D%3Dvalue%3B%0A%20%20%20%20%20%20%20%20%20%20break%3B%0A%20%20%20%20%20case%20%22tracks%22%3A%0A%20%20%20%20%20%20%20%20%20%20if%28collectionCopy%5Bid%5D.hasOwnProperty%28prop%29%29%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20collectionCopy%5Bid%5D%5Bprop%5D.push%28value%29%3B%0A%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20else%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20collectionCopy%5Bid%5D%5Bprop%5D%20%3D%20%5Bvalue%5D%3B%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%20%20%20%20%20%20%0A%20%20%7Delse%7B%0A%20%20%20%20delete%20collectionCopy%5Bid%5D%5Bprop%5D%3B%0A%20%20%7D%0A%20%20%20%20return%20collectionCopy%3B%0A%7D%0A%0A//%20Alter%20values%20below%20to%20test%20your%20code%0AupdateRecords%285439,%20%22artist%22,%20%22ABBA%22%29%3B%0A%0A&curInstr=9&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var collection = {
    "2548": {
      "album": "Slippery When Wet",
      "artist": "Bon Jovi",
      "tracks": [ 
        "Let It Rock", 
        "You Give Love a Bad Name" 
      ]
    },
    "2468": {
      "album": "1999",
      "artist": "Prince",
      "tracks": [ 
        "1999", 
        "Little Red Corvette" 
      ]
    },
    "1245": {
      "artist": "Robert Palmer",
      "tracks": [ ]
    },
    "5439": {
      "album": "ABBA Gold"
    }
};
// Keep a copy of the collection for tests
var collectionCopy = JSON.parse(JSON.stringify(collection));
// Only change code below this line
function updateRecords(id, prop, value) {
  if (!(value=="" &&collectionCopy[id].hasOwnProperty(prop) )){
    switch(prop){
     case "album":
     case "artist":
          collectionCopy[id][prop]=value;
          break;
     case "tracks":
          if(collectionCopy[id].hasOwnProperty(prop)){
            collectionCopy[id][prop].push(value);
           }
          else{
            collectionCopy[id][prop] = [value];
          }
    }      
  }else{
    delete collectionCopy[id][prop];
  }
    return collectionCopy;
}
// Alter values below to test your code
updateRecords(5439, "artist", "ABBA");
```
## Iterate with JavaScript While Loops
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0Avar%20i%20%3D%200%3B%0Awhile%28i%20%3C%205%29%20%7B%0A%20%20myArray.push%28i%29%3B%0A%20%20i%2B%2B%3B%0A%7D%0A&curInstr=18&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myArray = [];
// Only change code below this line.
var i = 0;
while(i < 5) {
  myArray.push(i);
  i++;
}
```
## Iterate with JavaScript For Loops
[PYH](http://www.pythontutor.com/javascript.html#code=var%20myArray%20%3D%20%5B%5D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0Avar%20myArray%20%3D%20%5B%5D%3B%0Afor%20%28var%20i%20%3D%201%3B%20i%20%3C%206%3B%20i%2B%2B%29%20%7B%0A%20%20myArray.push%28i%29%3B%0A%7D%0A&curInstr=19&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
var myArray = [];
// Only change code below this line.
var myArray = [];
for (var i = 1; i < 6; i++) {
  myArray.push(i);
}
```
## Iterate Odd Numbers With a For Loop
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0Afor%20%28var%20i%20%3D%201%3B%20i%20%3C%2010%3B%20i%20%2B%3D%202%29%20%7B%0A%20%20myArray.push%28i%29%3B%0A%7D%0A&curInstr=18&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myArray = [];

// Only change code below this line.
for (var i = 1; i < 10; i += 2) {
  myArray.push(i);
}
```
## Count Backwards With a For Loop
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0A%0Afor%20%28var%20i%20%3D%209%3B%20i%20%3E%200%3B%20i%20-%3D%202%29%20%7B%0A%20%20%20myArray.push%28i%29%3B%0A%7D&curInstr=18&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myArray = [];
// Only change code below this line.
for (var i = 9; i > 0; i -= 2) {
   myArray.push(i);
}
```
## Iterate Through an Array with a For Loop
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myArr%20%3D%20%5B%202,%203,%204,%205,%206%5D%3B%0A//%20Only%20change%20code%20below%20this%20line%0Avar%20total%20%3D%200%3B%0Afor%20%28var%20i%20%3D%200%3B%20i%20%3C%20myArr.length%3B%20i%2B%2B%29%20%7B%0A%20%20total%20%2B%3D%20myArr%5Bi%5D%3B%0A%7D%0A&curInstr=19&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myArr = [ 2, 3, 4, 5, 6];
// Only change code below this line
var total = 0;
for (var i = 0; i < myArr.length; i++) {
  total += myArr[i];
}
```
## Nesting For Loops
[PYH](http://www.pythontutor.com/javascript.html#code=function%20multiplyAll%28arr%29%20%7B%0A%20%20var%20product%20%3D%201%3B%0A%20%20//%20Only%20change%20code%20below%20this%20line%0A%20%20%0Afor%20%28var%20i%3D0%3B%20i%20%3C%20arr.length%3B%20i%2B%2B%29%20%7B%0A%20%20for%20%28var%20j%3D0%3B%20j%20%3C%20arr%5Bi%5D.length%3B%20j%2B%2B%29%20%7B%0A%20%20%20%20%20%20product*%3Darr%5Bi%5D%5Bj%5D%3B%0A%20%20%20%20%20%20console.log%28arr%5Bi%5D%5Bj%5D%29%3B%0A%20%20%20%20%20%20console.log%28arr.length%29%3B%0A%20%20%20%20%20%20console.log%28arr%5Bi%5D.length%29%3B%0A%20%20%7D%0A%7D%0A%20%20//%20Only%20change%20code%20above%20this%20line%0A%20%20return%20product%3B%0A%0A%7D%0A//%20Modify%20values%20below%20to%20test%20your%20code%0AmultiplyAll%28%5B%5B1%5D,%5B2%5D,%5B3%5D%5D%29%3B&curInstr=35&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  
for (var i=0; i < arr.length; i++) {
  for (var j=0; j < arr[i].length; j++) {
      product*=arr[i][j];
      console.log(arr[i][j]);
      console.log(arr.length);
      console.log(arr[i].length);
  }
}
  // Only change code above this line
  return product;

}
// Modify values below to test your code
multiplyAll([[1],[2],[3]]);
```
## Iterate with JavaScript Do...While Loops
[PYH](http://www.pythontutor.com/javascript.html#code=//%20Setup%0Avar%20myArray%20%3D%20%5B%5D%3B%0Avar%20i%20%3D%2010%3B%0A%0A//%20Only%20change%20code%20below%20this%20line.%0A%0Ado%20%7B%0A%20%20myArray.push%28i%29%3B%0A%20%20i%2B%2B%3B%0A%7Dwhile%20%28i%20%3C%205%29%0A&curInstr=4&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
// Setup
var myArray = [];
var i = 10;

// Only change code below this line.
do {
  myArray.push(i);
  i++;
}while (i < 5)
```
## Profile Lookup
[PYH](http://www.pythontutor.com/javascript.html#code=//Setup%0Avar%20contacts%20%3D%20%5B%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Akira%22,%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Laine%22,%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%220543236543%22,%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Pizza%22,%20%22Coding%22,%20%22Brownie%20Points%22%5D%0A%20%20%20%20%7D,%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Harry%22,%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Potter%22,%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%220994372684%22,%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Hogwarts%22,%20%22Magic%22,%20%22Hagrid%22%5D%0A%20%20%20%20%7D,%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Sherlock%22,%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Holmes%22,%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%220487345643%22,%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22Intriguing%20Cases%22,%20%22Violin%22%5D%0A%20%20%20%20%7D,%0A%20%20%20%20%7B%0A%20%20%20%20%20%20%20%20%22firstName%22%3A%20%22Kristian%22,%0A%20%20%20%20%20%20%20%20%22lastName%22%3A%20%22Vos%22,%0A%20%20%20%20%20%20%20%20%22number%22%3A%20%22unknown%22,%0A%20%20%20%20%20%20%20%20%22likes%22%3A%20%5B%22JavaScript%22,%20%22Gaming%22,%20%22Foxes%22%5D%0A%20%20%20%20%7D%0A%5D%3B%0A%0A%0Afunction%20lookUpProfile%28name,%20prop%29%7B%0A//%20Only%20change%20code%20below%20this%20line%0Avar%20i%3D0%3B%0Avar%20msg%3B%0Ado%7B%0A%20%20console.log%28contacts%5Bi%5D%5B%22firstName%22%5D%29%3B%0A%20%20if%28contacts%5Bi%5D%5B%22firstName%22%5D%3D%3Dname%29%20%7B%0A%20%20%20%20if%28contacts%5Bi%5D.hasOwnProperty%28prop%29%29%7B%0A%20%20%20%20%20%20msg%3Dcontacts%5Bi%5D%5Bprop%5D%3B%0A%20%20%20%20%7Delse%7B%0A%20%20%20%20%20%20%20%20msg%3D%22No%20such%20property%22%3B%0A%20%20%20%20%7D%0A%20%20%7D%0A%20%20i%2B%2B%3B%20%20%0A%7Dwhile%20%28i%3Ccontacts.length%20%26%26%20contacts%5B%22firstName%22%5D!%3Dname%29%0Aif%20%28!msg%29%0A%20%20%20msg%3D%22No%20such%20contact%22%3B%0Areturn%20msg%3B%0A//%20Only%20change%20code%20above%20this%20line%0A%7D%0A%0A//%20Change%20these%20values%20to%20test%20your%20function%0AlookUpProfile%28%22Akira%22,%20%22likes%22%29%3B&curInstr=24&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
//Setup
var contacts = [
    {
        "firstName": "Akira",
        "lastName": "Laine",
        "number": "0543236543",
        "likes": ["Pizza", "Coding", "Brownie Points"]
    },
    {
        "firstName": "Harry",
        "lastName": "Potter",
        "number": "0994372684",
        "likes": ["Hogwarts", "Magic", "Hagrid"]
    },
    {
        "firstName": "Sherlock",
        "lastName": "Holmes",
        "number": "0487345643",
        "likes": ["Intriguing Cases", "Violin"]
    },
    {
        "firstName": "Kristian",
        "lastName": "Vos",
        "number": "unknown",
        "likes": ["JavaScript", "Gaming", "Foxes"]
    }
];


function lookUpProfile(name, prop){
// Only change code below this line
var i=0;
var msg;
do{
  console.log(contacts[i]["firstName"]);
  if(contacts[i]["firstName"]==name) {
    if(contacts[i].hasOwnProperty(prop)){
      msg=contacts[i][prop];
    }else{
        msg="No such property";
    }
  }
  i++;  
}while (i<contacts.length && contacts["firstName"]!=name)
if (!msg)
   msg="No such contact";
return msg;
// Only change code above this line
}

// Change these values to test your function
lookUpProfile("Akira", "likes");
```
## Generate Random Fractions with JavaScript
[PYH](http://www.pythontutor.com/javascript.html#code=function%20randomFraction%28%29%20%7B%0A%0A%20%20//%20Only%20change%20code%20below%20this%20line.%0A%20%20return%20Math.random%28%29%3B%0A%0A%20%20//%20Only%20change%20code%20above%20this%20line.%0A%7D&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function randomFraction() {
  // Only change code below this line.
  return Math.random();
  // Only change code above this line.
}
```
## Generate Random Whole Numbers with JavaScript
[PYH](http://www.pythontutor.com/javascript.html#code=var%20randomNumberBetween0and19%20%3D%20Math.floor%28Math.random%28%29%20*%2020%29%3B%0A%0Afunction%20randomWholeNum%28%29%20%7B%0A%20%20//%20Only%20change%20code%20below%20this%20line.%0Avar%20randomNumberBetween0and9%20%3D%20Math.floor%28Math.random%28%29%20*%2010%29%3B%0A%20%20return%20randomNumberBetween0and9%3B%0A%7D%0Avar%20num%20%3D%20randomWholeNum%28%29%3B&curInstr=5&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);
function randomWholeNum() {
  // Only change code below this line.
var randomNumberBetween0and9 = Math.floor(Math.random() * 10);
  return randomNumberBetween0and9;
}
```
## Generate Random Whole Numbers within a Range
[PYH](http://www.pythontutor.com/javascript.html#code=function%20randomRange%28myMin,%20myMax%29%20%7B%0A%20%20return%20Math.floor%28Math.random%28%29%20*%20%28myMax-%20myMin%20%2B%201%29%29%20%2B%20myMin%3B%20%0A%7D%0A%0A//%20Change%20these%20values%20to%20test%20your%20function%0Avar%20myRandom%20%3D%20randomRange%285,%2015%29%3B&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function randomRange(myMin, myMax) {
  return Math.floor(Math.random() * (myMax- myMin + 1)) + myMin; 
}
// Change these values to test your function
var myRandom = randomRange(5, 15);
```
## Use the parseInt Function
[PYH](http://www.pythontutor.com/javascript.html#code=function%20convertToInteger%28str%29%20%7B%0A%20%20return%20parseInt%28str%29%0A%7D%0A%0AconvertToInteger%28%2256%22%29%3B&curInstr=3&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function convertToInteger(str) {
  return parseInt(str)
}
convertToInteger("56");
```
## Use the parseInt Function with a Radix
[PYH](http://www.pythontutor.com/javascript.html#code=function%20convertToInteger%28str%29%20%7B%0A%20%20var%20a%20%3D%20parseInt%28str,2%29%3B%0A%20%20return%20a%3B%0A%7D%0AconvertToInteger%28%2210011%22%29%3B&curInstr=3&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function convertToInteger(str) {
  var a = parseInt(str,2);
  return a;
}
convertToInteger("10011");
```
## Use the Conditional (Ternary) Operator
[PYH](http://www.pythontutor.com/javascript.html#code=function%20checkEqual%28a,%20b%29%20%7B%0A%20%20return%20a%20%3D%3D%20b%20%3F%20true%20%3A%20false%20%3B%0A%7D%0AcheckEqual%281,%202%29%3B&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function checkEqual(a, b) {
  return a == b ? true : false ;
}
checkEqual(1, 2);
```
## Use Multiple Conditional (Ternary) Operators
[PYH](http://www.pythontutor.com/javascript.html#code=function%20checkSign%28num%29%20%7B%0A%20%20return%20%28num%20%3E%200%29%20%3F%20%22positive%22%20%3A%20%28num%20%3C%200%29%20%3F%20%22negative%22%20%3A%20%22zero%22%3B%0A%7D%0A%0AcheckSign%2810%29%3B&curInstr=2&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
function checkSign(num) {
  return (num > 0) ? "positive" : (num < 0) ? "negative" : "zero";
}
checkSign(10);
```
