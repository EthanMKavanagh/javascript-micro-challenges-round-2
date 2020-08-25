# Loops, Arrays, and Nested Function Calls

Create a function that takes in an array of names. The function should return an array of strings, welcoming each person to Prime.

This function _must_ use the `welcome` function you wrote in the [100-Functions](./100-Functions.md) checkpoint. Copy/paste the `welcome` function you wrote into this file, in order to use it.

## Examples:

### Example 1

```js
let people = [
  "Ashley",
  "Yosef",
  "Jay"
];
welcomeAll(people);
```

should return 

```js
[
  "Hello Ashley, and welcome to Prime!",
  "Hello Yosef, and welcome to Prime!",
  "Hello Jay, and welcome to Prime!",
]
```

// Assignment
//-----------
let people = [
  "Ashley",
  "Yosef",
  "Jay"
];

let location = [
  "Prime"
];

function welcome( personName, personLocation ){
  for( i = 0; i < people.length; i++ ){
    let personStatement =  'Hello', people[ i ];
  } // end for
  for( i = 0; i < location.length; i++ ){
    let locationStatement = ', and welcome to', location[ i ] + '!';
  } // end for
  return personStatement + locationStatement;
} // end welcome

welcomeAll( people, location );

// I tried, lol. Git push anyways!