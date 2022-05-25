# Class 6 Reading Notes

## Intro to JS

JavaScript (JS) is a cross-platform, object-oriented scripting language used to make webpages interactive (e.g., having complex animations, clickable buttons, popup menus, etc.)

JS is considered the third layer of the layer cake of standard web technologies, the first two being HTML and CSS

**Application Programming Interfaces** (APIs) are ready-made sets of code building blocks that allow a developer to implement progreams that would otherwise be hard or impossible to implement

- Browser APIs are built into your web browser, and are able to expose data from the surrounding computer environment
  - the DOM (Document Object Model) API allows you to manipulate HTML and CSS, creating, removing and changing HTML, dnamically applying new styles to your page, etc.
  - The Geolocation API retreives geographical information

- Third party APIs are not built into the browser by default, and you generally have to grab their code and information from somewhere else
  - The Twitter API allows you to do things like displaying your latest tweets on your website

When the browser encounters a block of JS, it generally runs it in order, from top to bottom

### Interpreted versus compiled code

- In interpreted languages, the code is run from top to bottom and the result of running the code is immediately returned
- Compiled languages, on the other hand, are transformed (compiled) into another form before they are run by the computer

JavaScript is a lightweight interpreted programming language. It uses just-in-time compiling to improve performance, but it is still considered and interpreted language since the compiling is handled at run time, rather than ahead of time

### Server-side versus client-side code

- client-sde code is code run on the user's computer -- when a web page is viewed, the page's client-side code is downloaded, the run and displayed by the browser
- server-side code in run on the server, then its *results* are downloaded and displayed in the browser.

JS can be us as either, but when used on a web page it is client-side

### Dynamic versus static code

- dynamic code refers to the ability to update the display of a program to show different things in different circumstances, generating new content as required
- a web page with no dynamically updating content is referred to as static

JS is used to dynamically generate new content
