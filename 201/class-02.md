# Class 02 Reading Notes

## Introduction to HTML continued

It is important to use semantic elements to give the content the correct meaning, function, or appearance.

There are six levels of headings in HTML, `<h1>` to `<h6>`

The `<sup>` and `<sub>` elements are used to format text into superscript and subscript, respectively

When using the `<abbr>` element, the `title` attribute is required to provide the full expansion of the term.

## How CSS is Structured

CSS can be applied to HTML in three ways:

1. An external stylesheet, which contains CSS in a separate file with a `.css` extension

2. An in ternal stylesheet, which resides within an HTML document using a `<style>` element

3. Inline styles which affect a single HTML element contained within a `style` attribute. AVoid using inline styles as it is the least efficient implementation of CSS, and mixing CSS code with HTML makes everything more difficult to read.

```CSS
 h2 {
     color: black;
     padding: 5px;
   }
```

In the above code block, `h2` represents the selector, each line of text are the CSS declarations, with the properties being `color` and `padding`

## Learn JS

Variables in JS are enclosed in single quote marks

Examples of operators include addition `+`, assignment `=`, strict equality `===`, and not `!`

Functions execute a body of code when called, allowing it to be ureused without repeatedly writing the same code

### Conditionals

An if statement checks a condition and if it evaluates to true, then the code block will execute

`else if` is a way to chain extra choices/outcomes to `if...else` statements

Examples of comparison operators incldude `===` and `!==` (testing if one value is identical to another or not), `<` and `>` (testing if one value is less than or greater than another) , and `<=` `>=` (testing if one value is less than or equal to, or greater than or equal to, another)

`&&` is the logical and, chaining together two or more expressions so  that all of them have to individually evaluate to `true` for the whole expression to return `true`

`||` is the logical or, chaining together two or more expressions so that at least one of them have to individually evaluate to `true` for the whole expression to return `true`
