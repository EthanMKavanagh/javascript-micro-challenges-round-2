# Conditional Checkpoint

Create a function that takes a birth year (number) as an argument. Your function should return the name of the generation someone born in that year would belong to.

| Generation Name | Birth Years |
| --- | --- |
| Old Timer | 1945 and earlier |
| Baby Boomer | 1946 to 1964 |
| Gen X | 1965 to 1985 |
| Millennial | 1986 to 1996 |
| Gen Z | 1997 to now |

## Examples:

### Example 1

```js
myGeneration(1973);
```

should return 

```js
"Gen X"
```

### Example 2

```js
myGeneration(1922);
```

should return


```js
"Old Timer"
```

### Example 3

```js
myGeneration(2006);
```

should return


```js
"Gen Z"
```

// Assignment
//-----------
function myGeneration( birthYear ){
    if( birthYear <= 1945 ){
        return 'Old Timer';
    } // end if
    else if( 1946 <= birthYear <= 1964){
        return 'Baby Boomer';
    } // end else if
    else if( 1965 <= birthYear <= 1985 ){
        return 'Gen X';
    } // end else if
    else if( 1986 <= birthYear <= 1996 ){
        return 'Millennial';
    } // end else if
    else{
        return 'Gen Z';
    } // end else
} // end myGeneration

myGeneration( 1973 );
myGeneration( 1922 );
myGeneration( 2006 );