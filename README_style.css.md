**README.md**
=====================================

**File Overview**
-----------------

This file (`.\style.css`) is a CSS (Cascading Style Sheets) file used to customize the visual appearance and layout of an HTML document. It contains styles for the `<body>` element and `<button>` elements.

**What this file does**
-------------------------

This CSS file styles the HTML document by setting:

* The font family, text alignment, and margin of the `<body>` element
* The padding, font size, background color, text color, border, border radius, and cursor style of the `<button>` element
* The background color of the `<button>` element on hover

**Functions/Classes explained**
---------------------------------

### `<body>` styles

The styles for the `<body>` element are as follows:

* `font-family`: Sets the font family to Arial, which is a sans-serif font. The `sans-serif` value is set as a fallback in case the Arial font is not available.
* `text-align`: Centers the text within the `<body>` element.
* `margin-top`: Sets the top margin of the `<body>` element to 100 pixels.
* `background-color`: Sets the background color of the `<body>` element to a light gray color (`#f2f2f2`).

### `<button>` styles

The styles for the `<button>` element are as follows:

* `padding`: Sets the padding of the `<button>` element to 10 pixels horizontally and 20 pixels vertically.
* `font-size`: Sets the font size of the `<button>` element to 16 pixels.
* `background-color`: Sets the background color of the `<button>` element to a blue color.
* `color`: Sets the text color of the `<button>` element to white.
* `border`: Sets the border of the `<button>` element to none, which means it will not display a border.
* `border-radius`: Sets the border radius of the `<button>` element to 5 pixels, which means the corners will be rounded.
* `cursor`: Sets the cursor style of the `<button>` element to a pointing hand, indicating that it is clickable.

### `.hover` class

The CSS class `.hover` is applied to the `<button>` element on hover. It sets the background color of the `<button>` element to a darker blue color (`darkblue`), creating a hover effect.

**Dependencies used**
-------------------------

This CSS file does not rely on any external dependencies or libraries.

**Commit message guidelines**
---------------------------

When updating this CSS file, please follow the standard commit message guidelines:

* Use present tense (e.g., "Add new style for button")
* Use brief and descriptive subject line
* Use imperative mood (e.g., "Add padding to button")

**Contributing**
--------------

Contributions to this CSS file are welcome! Please submit a pull request with your changes and follow the project's guidelines for submitting code.