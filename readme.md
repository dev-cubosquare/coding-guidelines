# Cubosquare Coding Guidelines

## Table of Contents
- [Introduction](#introduction)
- [HTML Guidelines](#html-guidelines)
- [CSS Guidelines](#css-guidelines)
- [File Structure](#file-structure)
- [Conclusion](#conclusion)


## Introduction

In order to maintain consistency and readability in the code of the Cubosquare web development team, we have established a set of coding guidelines for HTML and CSS. These guidelines are based on industry standards and best practices, and should be followed by all members of the team.


## HTML Guidelines

1. Use semantic markup whenever possible. This means using HTML elements that have meaning and convey the purpose of the content, rather than using generic divs or spans.

1. Use lowercase for all HTML tags and attributes.

1. Use double quotes for all attribute values.

1. Use two spaces for indentation to make the code more readable. Indent nested elements by one level.

1. Use comments to explain the purpose of each section of code.

1. Do not use inline styles. Instead, use external CSS files to define styles.

1. Use HTML5 doctype: `<!DOCTYPE html>`

1. Use UTF-8 as the character encoding: `<meta charset="utf-8">`

1. Use alt attributes for all images: `<img src="./img/example.jpg" alt="Description of the image">` if the image is decorative, use an empty alt attribute: `<img src="./img/example.jpg" alt="">`

1. Use the HTML5 `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` elements to define the structure of the page.

1. Do not nest `<header>`, `<section>`, `<footer>` elements inside each other.

1. Use the `<div>` element to group elements together when there is no other suitable element available.

1. Use the `<span>` element to group inline elements together when there is no other suitable element available.

1. Use the `<strong>` element to indicate important text. If the text is bold for stylistic reasons, use CSS instead.

1. Use the `<em>` element to indicate emphasized text. If the text is italic for stylistic reasons, use CSS instead.


1. Use proper heading tags for page structure: `<h1>` for the main title, `<h2>` for section titles, and so on.

1. Use `<p>` tags for paragraphs of text.

1. Use `<ul>` and `<ol>` tags for unordered and ordered lists, respectively.

1. Use `<a>` tags for links. External links should have the `target="_blank"` attribute to open in a new tab.

1. Use `<input>` for buttons when there on specific reason to use `<button>`. Use the `type="submit"` attribute to submit a form when the button is clicked.

1. Use `<button>` tags for buttons. Use the `type="button"` attribute to prevent the button from submitting a form if it is not supposed to do so.

1. Use `<form>` tags for forms. Use the `action` attribute to specify the URL where the form data should be submitted. Use the `method` attribute to specify the HTTP method to use when submitting the form data.

1. Use `<input>` tags for form inputs. Use the `type` attribute to specify the type of input. Use the `name` attribute to specify the name of the input. All form inputs should have a `name` attribute. 

1. Use `<label>` tags for form labels. Use the `for` attribute to specify the `id` of the input that the label is for.

1. Use `<select>` tags for dropdown menus. Use `<option>` tags for the options in the dropdown menu.

1. Use `<table>` tags for tabular data. Use `<thead>`, `<tbody>`, and `<tfoot>` tags to define the table header, body, and footer, respectively. Use `<th>` tags for table headers. Use `<tr>` tags for table rows. Use `<td>` tags for table cells.


1. Do not use `<br>` tags for spacing. Instead, use CSS to add spacing between elements.

1. Do not use `<table>` tags for layout. Instead, use CSS to position elements.

1. Do not use deprecated HTML elements or attributes. For example, do not use `<center>` tags or the `align` attribute.

1. Use relative URLs for all links and images. For example, use `src="./img/example.jpg"` instead of `src="https://example.com/img/example.jpg"`.


## CSS/SCSS Guidelines

1. Use meaningful and descriptive class names. Avoid using single letters or abbreviations.

1. Use [BEM naming convention](https://getbem.com/) for class names. A BEM class name consists of three parts: the block, the element, and the modifier. For example, `.menu__item--active` would be a BEM class name for an active menu item.

1. Use two spaces for indentation to make the code more readable. Indent nested rules by one level.

1. Use lowercase for all CSS selectors and properties.

1. Use of scss is recommended. If you are using scss, use separate files for each component or section of the website. For example, you could have a `navigation.scss` file for the navigation bar, a `footer.scss` file for the footer, and so on.

1. Use variables to define colors, fonts, and other values that are used throughout the website. This will make it easier to make changes to the design in the future. For example, you could define a `$primary-color` variable for the primary color used throughout the website. or in css `--primary-color: #000;` and use it like this `color: var(--primary-color);`

1. Keep the code as simple as possible. Avoid using unnecessary selectors or properties.

1. Keep the code modular. Avoid using long selectors that are specific to a particular page or section of the website.

1. Use single line comments to explain the purpose of each section of code.

1. Use shorthand properties whenever possible to reduce the amount of code. For example, use `margin: 0` instead of `margin-top: 0; margin-right: 0; margin-bottom: 0; margin-left: 0;`.

1. Don't use reset but if you want use normalize.css instead.

1. Use media queries to create responsive designs that adapt to different screen sizes. There is no pre-defined breakpoints, you can define breakpoints according to design.

1. Avoid using `!important` unless absolutely necessary. It can make the code difficult to maintain and override.

## File Structure

Here is a recommended file structure for the Cubosquare web development team:

```yml
- index.html
- about.html
- contact.html
- css/
  - styles.css
  - ...
- img/
  - logo.png
  - background.jpg
  - ...
- js/
  - script.js
  - navigation.js
  - ...
- scss/
  - styles.scss
  - _variables.scss
  - _header.scss
  - ...
  
```

## Conclusion

These guidelines are not set in stone. They are meant to be a starting point for the Cubosquare web development team. Feel free to make changes to these guidelines as needed.