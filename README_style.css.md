# File Overview
===============

## `style.css`
================

This is a CSS (Cascading Style Sheets) file used for styling a web application.

# What this file does
----------------------

This file defines the visual styles for a web page, including font family, font size, colors, and layout. It specifically targets the `<body>` element and customizes the styles for buttons.

## Supported Browsers
-------------------

This CSS code is compatible with modern web browsers, including Chrome, Firefox, Safari, and Edge.

# Functions/Classes explained
-----------------------------

### `.body` Styles
------------------

*   `font-family: Arial, sans-serif;`: Sets the font family for the entire document to Arial, with sans-serif as a fallback.
*   `text-align: center;`: Centers the text horizontally within the `<body>` element.
*   `margin-top: 100px;`: Adds a margin of 100 pixels to the top of the `<body>` element.
*   `background-color: #f2f2f2;`: Sets the background color of the `<body>` element to a light gray color.

### `.button` Styles
--------------------

*   `padding: 10px 20px;`: Sets the padding around buttons to 10 pixels on the top and bottom, and 20 pixels on the left and right.
*   `font-size: 16px;`: Sets the font size for buttons to 16 pixels.
*   `background-color: blue;`: Sets the background color of buttons to blue.
*   `color: white;`: Sets the text color of buttons to white.
*   `border: none;`: Removes any border from buttons.
*   `border-radius: 5px;`: Adds a 5-pixel radius to the corners of buttons.
*   `cursor: pointer;`: Sets the cursor shape to a pointing hand when hovering over buttons.

### `.button:hover` Styles
---------------------------

*   `background-color: darkblue;`: Sets the background color of buttons to a darker blue color on hover.

# Dependencies used
--------------------

*   This file does not require any external dependencies, as it uses only native CSS properties.

# Example Usage
---------------

To apply these styles to an HTML page, include the CSS file in the `<head>` section of the document:
```html
<head>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
```
You can then use buttons with the specified styles in your HTML code:
```html
<button>Click me!</button>
```