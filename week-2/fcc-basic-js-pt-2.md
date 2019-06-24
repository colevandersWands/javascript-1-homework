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
