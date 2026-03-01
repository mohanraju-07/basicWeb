**READMe for .\style.css**
=========================

## File Overview
---------------

This file, `.style.css`, is a CSS (Cascading Style Sheets) stylesheet that defines the visual layout and styling of a web page. It is a single file containing essential CSS rules for styling the body, buttons, and button hover states.

## What this file does
----------------------

* It sets the font family and text alignment for the body content.
* It styles the buttons with a specific padding, font size, background color, text color, border, and border radius.
* It defines the hover state for buttons, changing the background color on mouse hover.

## Functions/Classes explained
-----------------------------

### `.body` selector

* Sets the font family to Arial (or a sans-serif font), ensuring text is consistently styled throughout the body.
* Aligns the text content to the center of the body element.
* Sets a top margin of 100px to create spacing between the top of the page and the content.
* Sets a background color to a light gray (`#f2f2f2`) for the entire body element.

### `.button` selector

* Styles the buttons with 10px of padding on the left and right sides, and 16px of font size for clear readability.
* Sets the background color to blue, providing a consistent visual cue for buttons.
* Sets the text color to white, ensuring text is readable on the blue background.
* Sets the border to none, removing any default border styles.
* Rounds the border radius to 5px, creating a smooth edge for the button.

### `.button:hover` pseudo-class

* Defines the hover state for buttons, changing the background color to a darker blue on mouse hover.
* This creates a visual effect that notifies users when the button is interactive.

## Dependencies used
--------------------

This stylesheet does not depend on any external libraries, frameworks, or other code. It is a self-contained stylesheet that can be used with any HTML document that includes these CSS selectors.

**Example Use Case:**

Include this stylesheet in your HTML file by adding the following line in the `<head>` section:
```html
<link rel="stylesheet" type="text/css" href=".style.css">
```
This will apply the styles defined in `.style.css` to your HTML document.