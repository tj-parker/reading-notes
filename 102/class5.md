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

### Internal CSS

An internal style is defined inside the `<style>` element, inside the head section

It may be used if one single HTML page has a unique style, but it is best practice to use an external style sheet

### Inline CSS

An inline style applies a unique style to a single element, by adding the style attribute. Again, it is best practice to use an external style sheet

## Cascading Order

If some properties have been defined for the same selector in different style sheets, the value from the last read style sheet will be used.

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

If the internal CSS is defined before the external style is linked, the external style would have higher priority because it is the last read
