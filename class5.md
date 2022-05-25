# Class 5 Reading Notes

## What is CSS

CSS (Cascading Style Sheets) is a language for specifying how documents are presented to users

CSS is a rule-based language -- you define the rules by specifying groups of styles that should be applied to particular elements or groups or elements on your web page

A CSS rule is written as follows:

```css
selector {
    property: value;
    property: value;
    property: value;
    }
```

The selector is the element being modified

## How to Add CSS

There are three ways of inserting a style sheet:

### External CSS

With an external style sheet, you can change the look of a website with a .css file referenced by the HTML page inside a `<link>` element:

> `<link rel="stylesheet" href="styles.css" />`

Here's an example of a .css stylesheet

``` css
body {
  background-color: lightblue;
}

h1 {
  color: navy;
  margin-left: 20px;
}
```
