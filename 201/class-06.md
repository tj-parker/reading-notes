# Class 06 Reading Notes

## JavaScript Object Basics

An object is a collection of related data and/or functionality.

Objects usually consist of several variables nad functions, which are called properties and methods, respectively, when inside an object

Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array because individual items can be identified by name

Bracket notation can be used to set not only member values dynamically, but also member names. Dot notation can only accept a literal member name, not a variable value pointing to aa name.

Dot notation:

```javaScript
person.age
person.name.first
```

Bracket notation:

```javaScript
person['age']
person['name']['first']
```

The `this` keyword refers to the current object the code is being written inside

```javaScript
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

In this code block, `this` is equivalent to `name` and `age`. `this` enables you to use the same method definiteion for every object you create

## Introduction to the DOM

The DOM (Document Object Model) is the date representation of the object that comprise the structure and content of a document on the web. The DOM represents the document as nodes and object, that way programming languages can interact with the page.

The DOM is an object-oriented representation of the web page. All elements in a document are part of the document object model that can be accessed and manipulated using the DOM and a scripting language such as javaScript.
