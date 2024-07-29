# dp98
Simple Portfolio Website Template
=====================================

## Overview

This is a simple portfolio website template designed to showcase your work and skills. The template includes a basic navigation menu that can be toggled on and off using a hamburger icon.

## Features

* Simple and responsive design
* Toggleable navigation menu
* Easy to customize and extend

## Code Structure

The code is organized into the following files:

* `script.js`: Contains the JavaScript code for toggling the navigation menu.
* `index.html`: Contains the HTML structure for the website (not shown).
* `styles.css`: Contains the CSS styles for the website (not shown).

## Usage

To use this template, simply clone the repository and open the `index.html` file in a web browser. You can customize the template by modifying the HTML, CSS, and JavaScript files.

## JavaScript Functionality

The `script.js` file contains a single function, `toggleMenu()`, which toggles the navigation menu on and off. The function targets the HTML elements with classes `.menu-links` and `.hamburger-icon`.

### toggleMenu() Function

```javascript
function toggleMenu() {
  const menu = document.querySelector(".menu-links");
  const icon = document.querySelector(".hamburger-icon");
  menu.classList.toggle("open");
  icon.classList.toggle("open");
}
