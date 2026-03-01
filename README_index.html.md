**README.md for `index.html`**
================================

# File Overview
---------------

This is a standalone HTML (HyperText Markup Language) file, serving as the entry point for a simple web application. The purpose of this file is to display a basic webpage layout and interact with associated script files.

# What this file does
--------------------

The `index.html` file:

* Defines the structure and content of an HTML document using various elements and attributes.
* Provides links to external stylesheet (CSS) and script files to enhance the appearance and functionality of the webpage.
* Displays a simple "Welcome" message and a clickable button.

# Functions/Classes explained
---------------------------

The following functions or classes are used in this file:

* **`changeText()` function**: This JavaScript function, referenced by the `onclick` attribute of the button element, is expected to be defined in the `script.js` file. Its purpose is to modify the text content of the `<p>` element with the `id` attribute "message".

# Dependencies used
-------------------

This file depends on the following external resources:

* **`style.css` file**: A linked stylesheet that defines the visual presentation of the HTML document. The link is specified in the `<head>` section with the `href` attribute.
* **`script.js` file**: A linked script file that contains the JavaScript code for the interactive functionality of the webpage. The link is specified in the `<body>` section.

**Please note:**

- The `script.js` and `style.css` files are not included in this README as they are assumed to be external resources created separately.
- This HTML file assumes the presence of the `script.js` and `style.css` files in the same directory.