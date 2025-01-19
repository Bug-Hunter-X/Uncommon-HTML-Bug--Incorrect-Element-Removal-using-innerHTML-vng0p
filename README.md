# Uncommon HTML Bug: Incorrect Element Removal

This repository demonstrates a subtle bug related to removing HTML elements using the `innerHTML` property.  While seemingly straightforward, directly setting `innerHTML` to an empty string doesn't always guarantee complete removal, potentially leaving behind lingering elements or causing unexpected issues with event listeners or other DOM manipulations.

The `bug.html` file showcases the incorrect implementation. The `bugSolution.html` file provides the correct solution using the `removeChild` method for reliable element removal.

This example highlights the importance of understanding the nuances of DOM manipulation in HTML and choosing the appropriate methods for specific tasks.  Using `removeChild` ensures clean and predictable removal of elements from the DOM.