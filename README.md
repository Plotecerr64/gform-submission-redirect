# Google Form Redirect After Submitting

This HTML document demonstrates how to embed a Google Form in an iframe and redirect the page after the form is submitted.

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Customization](#customization)

## Overview

This project consists of a simple HTML file that embeds a Google Form in an iframe. It uses JavaScript to detect when the iframe is reloaded (after the form is submitted) and redirects the page to a specified URL.

## Usage

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in a web browser.

## How It Works

- The HTML file includes an iframe with a Google Form URL.
- JavaScript is used to detect the iframe reloads. Upon the second reload (after form submission), the page is redirected to a specified URL.

## Customization

- **Google Form URL:** Replace the `src` attribute of the iframe with the URL of your Google Form.
- **Redirect URL:** Change the `document.location` in the JavaScript code to the desired URL where you want to redirect the user after form submission.
  
  ```javascript
  document.location = "https://example.com";
  ```
