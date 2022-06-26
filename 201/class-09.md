# Class 09 Reading Notes

## HTML Forms

Web Forms are a very powerful tool for interacting with users, commonly used for collecting data or allowing users to control a user interface

It's important to remember to keep a form simple and only ask for necessary data. The bigger the form, the larger the risk in frustrating and thus losing users.

The `<form>` element formally defines a form and attributes that determine the form's behavior. Each HTML form must start with this element

The `<fieldset>` element creates groups of widgets that share the same purpose, for styling and semantic purposes. The `<fieldset>` element can also be used to section a form. 

A `<fieldset>` cna be labeled using a `<legend>` element. The text inside a `<legend>` formally desciribes the purpose of the `<fieldset>` it is included inside, and is useful for making the form more accessible.

The `<label>` element is the formal way to define a label for an HTML form widget. This is the most important element to build accessible forms as screenreaders are able to define and describe the related instructions.

`<input>` elements allow users to input data into the form

## JavaScript Events

Events are actions or occurrences that happen in the system being programmed in, that the code can then react to. For example, if there is a button on a webpage, there can be code written that triggers when the button is clicked. The click is the event.

When using the `addEventListener()` method, you need a event written as a string that indicates what the method is listening to, and a function to call when the event happens.

Event objects are parameters specified inside and event handler function that is automatically passed to even handlers to provide extra features and information. The `target` property of the even object is always a reference to the element the event occured upon, ensuring the function triggered only affects what its supposed to

In the event capturing phase, the browser checkst to see if the element's outer-most ancestor had an event handler registered on it, and runs it if so. Then it moves on the the next element inside and does the same, and then the next one, and so on until it reaches the direct parent of the element that the even actualyl registered. 

The bubbling phase is the exact opposite of the capturing phase. The browser checks to see if the direct parent of the element has an event handler registered on it, than runs it if so. Then it moves on to the next immediate ancestor element and does the same, so on until it reaches the `<html>` element. 