# Arrays Checkpoint

Create a function that takes in an array. Remove the first item in the array, move it to the end, and return the resulting array.

## Examples:

### Example 1

```js
arrayRotator(['a', 'b', 'c', 'd']);
```

should return 

```js
['b', 'c', 'd', 'a']
```

### Example 2

```js
arrayRotator([3, 5, 7, 9, 11]);
```

should return 

```js
[5, 7, 9, 11, 3]
```

### Example 2

```js
arrayRotator(["bananas", "potatoes", "eggs"]);
```

should return 

```js
["potatoes", "eggs", "bananas"]
```

// Assignment
//-----------
function arrayRotator( arr ){
    const rotatedArray = arr.concat();
    frontItem = rotatedArray.shift();
    rotatedArray.push( frontItem );
    return rotatedArray;
} // end arrayRotator

arrayRotator( [ 'a', 'b', 'c', 'd' ] );
arrayRotator( [ 3, 5, 7, 9, 11 ] );
arrayRotator( [ 'bananas', 'potatoes', 'eggs' ] );