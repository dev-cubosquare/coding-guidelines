# Cubosquare Coding Recommendations

## Table of Contents
- [Table of Contents](#table-of-contents)
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

1. Use alt attributes for all images: `<img src="example.jpg" alt="Description of the image">` if the image is decorative, use an empty alt attribute: `<img src="example.jpg" alt="">`

1. Use proper heading tags for page structure: `<h1>` for the main title, `<h2>` for section titles, and so on.

## CSS Guidelines

1. Use BEM naming convention for class names. A BEM class name consists of three parts: the block, the element, and the modifier. For example, `.menu__item--active` would be a BEM class name for an active menu item.

1. Use meaningful and descriptive class names. Avoid using single letters or abbreviations.

1. Use two spaces for indentation to make the code more readable. Indent nested rules by one level.

1. Use comments to explain the purpose of each section of code.

1. Use shorthand properties whenever possible to reduce the amount of code. For example, use `margin: 0` instead of `margin-top: 0; margin-right: 0; margin-bottom: 0; margin-left: 0;`.

1. Use lowercase for all CSS selectors and properties.

1. Don't use reset but if you want use normalize.css instead.

1. Use media queries to create responsive designs that adapt to different screen sizes.

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
- js/
  - script.js
  - navigation.js
  - ...
- img/
  - logo.png
  - background.jpg
  - ...
```

## Conclusion

By following these guidelines and file structure, we can ensure that our HTML and CSS code is consistent, readable, and maintainable. Using two spaces for indentation will help to create a consistent and readable codebase. The recommended file structure will help to keep our project organized and easy to navigate. This will make it easier for team members to work on the codebase, as well as for future developers who may need to make changes or additions.