# Function Checkpoint

Create a function that takes two strings as arguments: a person's name, and a location.

Your function should return a new string that welcomes the person to the location.

## Examples:

### Example 1

```js
welcome("Jonda", "Prime");
```

should return 

```js
"Hello Jonda, and welcome to Prime!"
```

### Example 2

```js
welcome("Neil", "the moon");
```

should return

```js
"Hello Neil, and welcome to the moon!"
```

// Assignment
//-----------
function welcome( personName, personLocation ){
    return 'Hello', personName + ', and welcome to', personLocation + '!';
} // end welcome

welcome("Jonda", "Prime");
welcome("Neil", "the moon");