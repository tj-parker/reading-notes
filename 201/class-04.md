# Class 04 Reading Notes

## Creating Hyperlinks

To create a hyperlink, wrap the text or other content inside an `<a>` element using the `href` attribute, which contains the web address

To ensure links are accessible to all readers, ensure link text can be read out of context (avoid using "click here"), are descriptive, and include keywords for search engines. Don't repeat the URL as part of the link text, and keep the link text as short as possible

## CSS Layout

### Normal Flow

Normal flow is the way webpage elements lay themselves out if you haven't changed their layout. It is designed to make a readable document even if the user is using a very limited browser

### Block Level vs Inline Elements

Block level element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content

The size of inline elements is just the size of their content. You cannot set width of height on inline elements, though you can set it to behave like a block level element

Each block-level element will appear on a new line below the last one, with each oen separated by whatever margin that's been specified. Inline elements, conversely, all sit on the same line along with any adjecent text content as lon as there is space for them to do so inside the width of the parent block element.

### Positioning

Static positioning is the default for every html element

With absolute positioning, the element no longer exists in the normal document flow, instead sitting on its own laer separate from everything else. This is useful because it allows the creation of isolated UI features that don't interfere with the layout of other elements on the page.

While absolute positioning fixes an element in place relative to its nearest positioned ancestor, fixed postioning usually fixes an element in place relative to the visible portion of the viewport. The two otherwise behave the same

## Functions

To declare a function, give it a name and then write the statements needed to achieve its task inside the curly braces. When you invoke a function, you execute the code that was declared.

Parameters act liek variables in a function. When you call a funciton that has parameters, you specify the values it should use in the parentheses that follow its name. These values are called arguments

## Pair Programming

Pair programming has many benefits, including learning from the different approaches of your partners and greater efficiency