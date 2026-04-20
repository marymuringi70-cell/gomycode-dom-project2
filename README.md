
In this project, you will build a simple interactive webpage that allows users to change the color of a box by clicking a button.

* The **HTML file** sets up the structure of the webpage, including a heading, a colored box, and a button.
* The **CSS file** adds styling to make the page visually appealing.
* The **JavaScript file** adds interactivity by changing the color of the box when the button is clicked.
* A function called **`getRandomColor()`** generates a random hexadecimal color.
* Each time the button is clicked, a new random color is applied to the box.

---

## 🛠️ Instructions

### 1. HTML Setup

* Create a new HTML file.
* Add the basic structure:

  * `<!DOCTYPE html>`
  * `<html>`, `<head>`, and `<body>` tags.
* Set the page title to **"Color Changer"**.

---

### 2. Create the Interface

Inside the `<body>`:

* Create a `<div>` with class `"container"`.
* Add an `<h1>` with the text **"Color Changer"**.
* Add a `<div>` with the id `"color-box"` (this is the box that changes color).
* Add a `<button>` with the id `"change-color-btn"` and text **"Change Color"**.

---

### 3. Styling with CSS

* Create a CSS file and link it using the `<link>` tag.
* Style the `.container`:

  * Center content horizontally
  * Add top margin for spacing
* Style `#color-box`:

  * Set fixed width and height
  * Add a default background color
* Style `#change-color-btn`:

  * Make it visually appealing
  * Ensure it's easy to click

---

### 4. JavaScript for Interactivity

* Create a JavaScript file and link it using the `<script>` tag.
* Use the `DOMContentLoaded` event to ensure the page loads before scripts run.
* Select elements using:

  ```javascript
  document.getElementById()
  ```
* Create a function called `getRandomColor()`:

  * Generates a random color (hex or RGB)
* Add a click event listener to the button:

  * When clicked, change the background color of the box

---

### 5. Testing

* Open your HTML file in a web browser.
* Click the **"Change Color"** button.
* Observe the box changing to a random color each time.

---

## 💡 Bonus Ideas

* Display the current color code on the screen
* Add smooth transition effects
* Change the entire page background color
* Add a reset button

---

## 🎯 Goal

By completing this project, you will understand:

* Basic HTML structure
* CSS styling techniques
* JavaScript DOM manipulation
* Event handling and interactivity


