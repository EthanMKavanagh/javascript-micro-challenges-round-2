# Loops and Arrays Checkpoint

Create a function that takes in an array of numbers, and returns the sum of those numbers.

## Examples:

### Example 1

```js
sum([3, 12]);
```

should return 

```js
15
```

### Example 2

```js
sum([3, 10, 100]);
```

should return 

```js
113
```

// Assignment
//-----------
function sum( arr ){
    let returnedSum = arr.reduce( ( a, b ) => a + b, 0 );
    return returnedSum;
} // end sum

sum([3, 12]);
sum([3, 10, 100]);