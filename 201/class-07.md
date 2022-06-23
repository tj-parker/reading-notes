# Class 07 Reading Notes

## Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A domain model that's articulated well can verify and validate your understanding of that problem.

## HTML Table Basics

Tables used to e common for page layouts because CSS support across browers was not good, however nowadays they should not be used for page layouts because they reduce accessibility for the visually impaired by not meshing well with screenreaders, they involve ore complex markup structure making the code harder to write, maintain, and debug, and they are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work.

The content of every table is enclosed by `<table>` and `</table>`. The table cell is created by a `<td>` element. To group cells into a row, use the `<tr>` tag.

## Introducing Constructors

A constructor is a function called using the `new` keyword. COnstructos allow us to create as many objects as we need by just updating the values of the properties that are different, using just a single object definition.

In an object literal `this` refers to the current object the code is being written inside, but in a constructor `this` is bound to the new object

## Object Prototypes Using a Constructor

An object inherits properties from another object known as its prototype. An object can call any methods defineed in its prototype.
