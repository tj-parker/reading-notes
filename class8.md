# Class 8 Reading Notes

## Operators

JavaScript has both *binary* and *unary* operators

- a binary operator requires two operands, one before the operator and one after

  - `x + y`

- a unary operator requires a single operand, either before or after the operator

  - `x++` or `++x`

There is also one ternary operator, the conditional operator

`condition ? x : y`

If `condition` is true. the operator has the value of `x`. Otherwise it has the value of `y`

### Assignment operators

An assignment operator assigns a value to its left operand based on the value of its right operand

`x = f()`

the value of `f()` is assigned to `x`

There are also compound assignment operators like:

`x += f()`

which assigns the value of `x + f()` to `x`

### Comparison operators

A comparison operator compares its operands and returns a logical value base on whether the comparion is true.

`var1 > var2` would return `true` if `var1` value was indeed greater than `var2`

## Loops

Loops repeat an action some number of times, offering a quick and easy way to do something repeatedly

### `for` statement

A `for` loop repeats until a specified condition evaluates to false

```javascript
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
```

1. The initializing expression `initialExpression` is executed

2. The `conditionExpression` expression is evaluated. If true, the loop statements execute. Otherwise the `for` loop terminates

3. The `statement` executes

4. If present, the update expression `incrementExpression` is executed.

5. Control returns to step 2

### `while` statement

A `while` statement executes its statements as long as a specified condtion evaluate to `true`

```javascript
while (condition)
  statement
```

If the condition returns `true`, `statement` is executed and the `condition` is tested again

If the `condition` becomes `false`, `statement` within the loop stops executing and control passes to the statement following the loop

Avoid infinite loops. Make sure the condition in a loop eventually becomes `false`, otherwise the loop will never terminate