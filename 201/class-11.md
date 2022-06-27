# Class 11 Reading Notes

## Video and Audio Content

In the early days HTML did not have the ability to embed video and audio on the web, and relied on proprietary technology like Flash. The HTML5 specifications added `<video>` and `<audio>` elements allowing for native audio and video support

In the same way as for the `<img>` element, the `src` attribute contains a path to what's being embeded. The `controls` attribute must be included in order to include the browser's conttrol interface, or build an interface using a JavaScript API.

Fallback content is displayed if the browser accessing the page doesn't support the `<video>` element, providing a fallback for older browsers

## Grid Layout

Grid Layout is a two-dimensional grid-based layout system, unlike Flexbox which is one-directional.

The Grid container is the direct parent of all the grid items

The Grid items are the children of the grid container

The Grid lines are the dividing lines, either vertical or horizontal that make up the structure of the grid

## Responsive Images

Responsive images solves several issues. A large image takes up a lot of screenspace on a smaller device such as a phone, however a smaller image will look grainy when blown up on a larger device like a laptop. Large images can also eat bandwidth for mobile users. Vector images can sometimes solve these problems, but they aren't ideal for complex and detailed images.

`srcset` defines the set of images the browser is allowed to choose between and what size each image is. `srcset` is more responsive than using CSS or JavaScript as when a browser starts to load a page any image starts to download befor the CSS and JavaScript are loaded

`sizes` defines a set of media conditions, such as screen width, and indicates what image size would be best to choose
