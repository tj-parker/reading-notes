# Class 01 Reading Notes

## Structure

HTML pages are text documents

HTML code is made up of characters that live inside angled brackets called **elements**

- elemtents are usually made up of two **tags** that sit inside angled brackets, one opening and one closing (the closing tag has a forward slash after the < symbol)
- each HTML element tells the browser something about the information that sits between its opening and closing tags

Attributes provide additional information about the contents of an element. They appear on the opening tag and are made up of a **name** and **value**, separated by an equals sign.

- The attribute name indicates what kind of extra information is being supplied. It should be written in lowercase
- The value is the information or setting for the attribute. It should be placed in double quotes

## Extra Markup

Some characters are used in and reseved by HTML code, so if you want these characters to appear on your page you need to use "escape" characters

- For example, `<` is used in tags, so if you wanted to use a less-than sign you would instead have to enter `&lt;` or `&#60;`

`DOCTYPES` tell browsers which verion of HTML you are using

You can add comments to your code between the `<!--` and `-->` markers

The `id` and `class` attributes allow you to identify particular elements

- `id` is used to uniquely identify an element from other elements on the page
- `class` is used to to identify several elemnts as being different from the other elements

The `<div>` and `<span>` elemnts allow you to group block-level and inline elements together, respectively

`<iframes>` cut windows into your web pages through which other pages can be displayed, such as to embed a Google Map to a page

The `<meta>` element lives inside the `<head>` element and contains informaiton about that web page

## HTML5 Layout

