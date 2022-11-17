# Class 03 Reading Notes

## React Docs - lsits and keys

The `map()` function takes in an array and returns a new array after applying a function to the array values
To loop through an array and display each value in JSX, use `map()`
Each list item needs a unique key, which helps React identify which items have changed, are added, or are removed.

## The Spread Operator

The spread operator `...` is used to expand an iterable object, usually an array, into the list of arguments
The spread operator can be used to copy an array, concatenate or combine arrays, used for Math functions, or for using an array as an argument

### Combining two arrays

```javascript
const arr1 = [1, 2, 3]
const arr2 = [4, 5, 6]
const arr1AndArr2 = [...arr1,...arr2]
console.log(...arr1AndArr2) // 1 2 3 4 5 6 \
```

### Adding to an array

```javascript
const arrA = ['yellow', 'blue']
const arrB = ['red', ...arrA]
console.log(arrB) // Array(3) ["red", "yellow", "blue"]
```

### Combining Objects

```javascript
const object1 = {first: "one"}
const object2 = {second: "two"}
const object3 = {...object1, ...object2, third: "three"}
console.log(object3) // Object { first: "one", second: "two", third: "three"}
```

## Pass Functions Between Components

The first step a developer does to pass functions between compoents is to create the function wherever the state is that is being changed

The increment function in the video is passed an object. Iterating through each item in the object, if there is a match with the name, it increments the count for the object that name belongs to

To pass a method from a parent component into a child component, pass `{this.method}` into the child component, and invoke it calling `this.props.method()`
