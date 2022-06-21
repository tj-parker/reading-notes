# Class 03 Reading Notes

## Ordered and Unordered Lists

Unordered lists (`<ul>`) are for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless

The bullet style can be defined using the `list-style-type` CSS property. It can be changed with attributes as well though this is not recommended as it has been deprecated

Use an ordered list (`<ol`) when the order is meaningful.

You can change the numbers on list items using the `type` attribute in conjunction with a numbering type: `a` for lowercase letters, `A` for uppercase, `i` for lowercase Roman numerals, `I` for uppercase Roman numerals, and `1` for numbers, which is the default.

## The Box Model

The four parts of the CSS box model are the content, the padding that sits arround the content, the border that wraps the content and any padding, and the margin that wraps all three as the whitespace between this box and other elements.

## Arrays, Operators, Expressions, Conditionals, Loops

### Arrays

Arrays can store varius data types including strings, numbers, objects, and even other arrays

Items in an array are assigned a number starting from zero called an *index*. Individual items can be accessed using bracket notation

An array inside an array is called a multidimensional array, and the item inside that array can be accessed by chaining two sets of brackets together

### Operators and Expressions

There are compound assignment operatos that are shorthand for other operations, including:

- `x += f()` shorthand for `x = x + f()`

- `x *= f()` shorthand for `x = x * f()`

- `x %= f()` shorthand for `x = x % f()`

- `x &= f()` shorthand for `x = x % f()`

- `x &&= f()` shorthand for `x && (x = f())`

```html
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```

This expresion would output `10dog`, since `c` is `false` the expression inside the parentheses would just result in `a`, leaving a concatention of `a` and `b`

### Conditonals

COnditional statements allow is to represent real world decision making in JavaScript by carrying out different actions dependinging on the inputs

For example, if the number of lives in a video game reaches zero, than the player receives a game over

### Loops

Loops are useful as they allow the user to do the same thing over and over again without having to run the code multiple times.
