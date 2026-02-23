[# error-display-js
](https://page-error-display.netlify.app/)

# JavaScript DOM Manipulation Practice

## Overview
This project demonstrates basic DOM manipulation using JavaScript. When a user clicks the purchase button, an error message is displayed dynamically in the browser.

## What I Learned
- How to select elements using `document.getElementById()`
- How to create and call JavaScript functions
- How to update HTML content using `.textContent`
- Basic event-driven interaction

## JavaScript Code
```javascript
let errorMess = document.getElementById("error")

function displayError() {
    errorMess.textContent = "Something went wrong, please try again"
}
