# Class 4 Reading Notes

## Wireframe and Design

A wireframe is a low fidelity, black & white sketch of a digital interface, used to plan the layout and interaction of the interface without any code

Wireframes can be drawn by hand, or using software

Effective UX design utilizes user research to determine what layout would be most effective for the auidence to use

- this could mean analyzing similar products, studying prevailing UX trends and best practices, and reviewing your own internal design guidelines
- have a strong concept of "user flow", or how the user interacts with the page from where they enter to where they end up, ensuring the user can remain self-suifficient throughout

A wireframe is just a sketch, ignore the fine detials and focus on representing the features and formats in as simple of a way as possible

- add details only to aid usability going into user tests

Once the first prototype is deemed effective, you can adapt it into a more high fidelity prototype

## HTML Basics

HTML (**H**yper**T**ext **M**arkup **L**anguage) is the code that is used to structure a web page and its content

HTML consists of a series of "elements" which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way

An element is composed of an opening tag (the name of the element wrapped in angle brackets), the closing tag (the same as the opening tag but includes a forwad slash before the element name), and the content in between the tags

Elements can also have attributes that contain extra information about the element that don't appear in the content

- for example, the `class` attribute allows you to give the element a non-unique identifier that can be used to target it and any other element with the same class
- an attribute should always have a space between it and the element name, an equal sign following the attribute name, and the attribute value wrapped by quotation marks

Elements can be put inside other elements, this is called **nesting**

**Empty Elements** have no content and thus need no closing tag

- The `<img>` tag is an example of an empty element

### Anatomy of an HTML document

    <!DOCTYPE html>
    <html>
     <head>
      <meta charset="utf-8">
      <title>My test page</title>
     </head>
     <body>
      <img src="#" alt="My test image">
     </body>
    </html>

`<!DOCTYPE html>` is required at the start of any HTML document

`<html></html>` wraps all the content on the page, sometimes reffered to as the root element

`<head></head>` a container for stuff that isn't content being shown, such as SEO terms, CSS, etc

`<meta charset="utf-8">` sets the charact set to UTF-8 which includes most characters from  the vast majority of written languages

`<title></title>` sets the title that appears in the browser tab

`<body></body>` contains all the content you want to show to web users

`<img>` elements contain a `src` attribute that contain the path to the image file, and an `alt` attribute to specify a descriptive text for users who cannot see the image

#### Essential HTML Elements

Heading elements allow you to specify up  to six heading levels, using `<h1>` to `<h6>`

`<p>` elements are for containing paragraphs of text

Lists can either be ordered with `<ol>` or unordered with `<ul>`, with the list items put inside `<li>` elements

`<a>` anchor elements are used in conjuction with an `href` attribute to create links
