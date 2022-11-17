# Class 05 Reading Notes

## React Docs - Thinking in React

The "single responsibility prionciple" is the idea that a component should only do one thing.

To build a static version of your app you'll want to build components that reuse other components and pass data using props

One you have a static application, ass the minimal (but complete) representation of the UI state

Three questions to ask to identify if something is state:

  1. is it passed in from a parent via props?
  2. does it remain unchanged over time?
  3. can you compute it based on any other state or props in your component?

If the answer to any of the above is yes, then it probably isn't state

State should live in the common owner component (a single compoent above all the components that need the state) or another component higher up in the hierarchy.

## Higher-Order Functions

A higher-order function is a function that operates on other function, either by taking them as arguments or by returning them

```javascript
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true
```

line 2 of the higher-order function is creating a new function
`reduce` operates as higher-order functions as it is passed a callback function as argument
