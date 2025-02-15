# PACET CampusBloodDonation
# Blood Donation & Requesting System

## Overview
The **Blood Donation & Requesting System** is a web-based platform designed to facilitate blood donation and requests within a campus or community. It allows donors to register, individuals to request blood, and provides contact information for blood banks.

## Features
- **Home Page**: Introduction to the platform.
- **Donor Registration**: Allows users to register as blood donors by providing necessary details.
- **Request Blood**: Users can request blood by filling out a form with required details.
- **Blood Bank Contacts**: Displays contact information for available blood banks.
- **Responsive Background**: Changes dynamically based on the user's device (desktop or mobile) using CSS.

## Technologies Used
- **HTML**: Structure of the website.
- **CSS**: Styling and responsive design.

## How to Use
1. Open the website in a web browser.
2. Navigate using the menu:
   - Click **Home** to see the welcome message.
   - Click **Donate** to register as a blood donor.
   - Click **Request Blood** to request a specific blood group.
   - Click **Contact** to view blood bank details.
3. The background adapts based on the device being used (desktop or mobile).

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repository-link
   ```
2. Open the `index.html` file in a web browser.

## Contributing
If you wish to contribute, feel free to fork the repository and submit a pull request with improvements or additional features.


# HTML & CSS Basics

## Introduction
This repository serves as a beginner-friendly guide to understanding the fundamentals of HTML and CSS. HTML (HyperText Markup Language) is the standard language used to create web pages, while CSS (Cascading Style Sheets) is used to style and layout web content.

## What is HTML?
HTML is the backbone of any web page. It consists of a series of elements that structure and define the content of a website.

### Basic HTML Structure:
```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to HTML & CSS Basics</h1>
    <p>This is a simple paragraph.</p>
</body>
</html>
```
### Common HTML Elements:
- `<h1> to <h6>`: Heading tags, with `<h1>` being the largest and `<h6>` the smallest.
- `<p>`: Paragraph tag for text content.
- `<a href="URL">`: Anchor tag for creating hyperlinks.
- `<img src="image.jpg" alt="Description">`: Displays images.
- `<ul>`, `<ol>`, `<li>`: Used for unordered and ordered lists.
- `<div>`: A container for grouping elements.
- `<span>`: Inline container for text styling.

## What is CSS?
CSS is used to style HTML elements and control their layout.

### Basic CSS Syntax:
```css
/* This is a CSS comment */
body {
    background-color: lightgray;
    font-family: Arial, sans-serif;
}
h1 {
    color: blue;
    text-align: center;
}
p {
    font-size: 16px;
    line-height: 1.5;
}
```
### CSS Selectors:
- `element`: Targets all instances of a specific element (e.g., `p { color: red; }`)
- `#id`: Targets a specific element by ID (e.g., `#header { font-size: 20px; }`)
- `.class`: Targets elements by class name (e.g., `.button { background: green; }`)

### Ways to Apply CSS:
1. **Inline CSS**: Applied directly inside the HTML tag using the `style` attribute.
   ```html
   <p style="color: red;">This is a red paragraph.</p>
   ```
2. **Internal CSS**: Defined within a `<style>` block inside the `<head>` section of an HTML file.
3. **External CSS**: Stored in a separate `.css` file and linked to the HTML file using `<link rel="stylesheet" href="styles.css">`.

## Getting Started
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/html-css-basics.git
   ```
2. Open `index.html` in a browser to view the basic structure.
3. Modify `styles.css` to see the effects of CSS on the webpage.

## Contributing
Feel free to contribute by adding more examples or improving the explanations.

## License
This project is licensed under the MIT License.

