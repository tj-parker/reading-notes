# Class 7 Reading Notes

## Control Flow

The control flow is the order in which the computer executes statements in a script

Code is run in order from the first line to that last, unless the computer runs accros structures that change the control flow, such as conditionals, loops, and functions.

## Functions

A JavaScript function is a block of code designed to perform a particular task, that is executed when something calls it

- it is defined with the `function` keyword, followed by a name, followed by parentheses

  - the parentheses may include parameter names separated by commas

- the code to be executed by the function is placed inside curly brackets

```javascript
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```

When JS reaches a `return` statement, the function will stop executing

Functions are helpful because you can reuse the code many times with different arguments to produce different results

### Local Variables

Variable declared within a JS function can only be accessed from within the function, meaning they are "local" to it

```javascript
// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName
```

Since local variable are only recognized inside their functions, variable with the same name can be used in different functions

## Operators

### Arithmetic Operators

Arithmetic operators are used to perform arithmetic on numbers:

| Operator   | Description   |
| :------: | :-------: |
|  +  | Addition |
|  -   | Subtraction  |
| *   | Multiplication|
| ** | Exponentiation |
| / | Division |
| % | Modulus (Division Remainder) |
| ++ | Increment |
| -- | Decrement |

### Assignment Operators

Assignment operators assign values to JavaScript variables.

Operator | Example | Same As |
| :----: | :-----: | :-----: |
| = | x = y | x = y |
| += | x += y | x = x + y |
| -= | x -= y | x = x - y |
| *= | x *= y | x = x * y |
| /= | x /= y | x = x / y |
| %= | x %= y | x = x % y |
| **= | x **= y | x = x ** y|

### Concatenation

The `+` and `+=` operators can also be used to add (concatenate) strings

```js
let text1 = "Hello";
let text2 = "World";
let text3 = text1 + " " + text2;
```

```js
let text1 = "Hello ";
text1 += "World";
```

Both codes would output "Hello World"

Adding two numbers will return the sum, but concatenating a number and a string will return a string

### Comparison Operators

| Operator | Description |
| :-----: | :----: |
| == | equal to |
| === | equal value and equal type |
| != | not equal |
| !== | not equal value or not equal type |
| > | greater than |
| < | less than |
| >= | greater than or equal to |
| <= | less than or equal to |
| ? | ternary operator |

### Logical Operators

| Operator | Description |
| :----: | :-----: |
| && | logical and |
| &#124;&#124; | logical or |
| ! | logical not |
