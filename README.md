# Natthapath Damrongsri - UX/UI Designer Portfolio

This is the source code for the personal portfolio website of Natthapath Damrongsri, a UX/UI Designer based in Bangkok. The portfolio showcases projects and provides contact information.

## Table of Contents

* [Overview](#overview)
* [Structure](#structure)
* [Technologies Used](#technologies-used)
* [Getting Started](#getting-started)
* [Customization](#customization)
* [Contact](#contact)

## Overview

The website is designed to present Natthapath Damrongsri's skills and experience as a UX/UI Designer. It includes the following sections:

* **Header:** Contains the designer's name/logo and navigation links to the "About," "Portfolio," and "Contact" sections.
* **Hero:** Introduces Natthapath with their name, title, and a brief tagline.
* **Portfolio:** Displays a grid of selected projects with brief descriptions and a "More" button to view additional details in a modal.
* **Contact:** Provides contact information, including email, phone number, and a link to LinkedIn.
* **Footer:** Contains copyright information.
* **Modals:** Display detailed information about each project when the "More" button is clicked.

## Structure

The project consists of the following files:

* `index.html`: The main HTML file containing the structure and content of the website.
* `styles.css`: The CSS file responsible for the styling and layout of the website.
* `script.js` (inline in `index.html`): Contains the JavaScript code for handling the modal functionality.

## Technologies Used

* HTML5: For structuring the content of the website.
* CSS3: For styling the layout and appearance of the website.
* JavaScript: For adding interactive elements, specifically the modal functionality.

## Getting Started

To view this portfolio website locally:

1.  **Clone or download** the repository containing these files.
2.  **Open** the `index.html` file in your web browser.

No additional setup or installation is required.

## Customization

To customize this portfolio for your own use:

1.  **Update Content in `index.html`:**
    * Modify the `<title>` tag.
    * Change the name in the header (`<h1>`).
    * Update the "About" section content (`<section id="about">`).
    * Replace the project information in the "Portfolio" section (`<section id="portfolio">`), including:
        * Placeholder image URLs (`<img src="...">`). Replace these with your project images or use a placeholder service.
        * Project titles (`<h3>`).
        * Project descriptions (`<p>`).
        * Update the modal content (`<div id="[project-name]-modal" class="modal">`) with detailed information about each project.
    * Update the contact information in the "Contact" section (`<section id="contact">`).
    * Modify the copyright information in the footer (`<footer>`).
    * Update the LinkedIn link with your profile URL.
    * Adjust the placeholder text in the "Project" divs within the portfolio grid.

2.  **Customize Styling in `styles.css`:**
    * Modify the colors, fonts, layout, and other visual aspects to match your personal branding.
    * Adjust the responsive design breakpoints in the `@media` queries as needed.

3.  **Extend Functionality (Optional):**
    * Add more interactive elements using JavaScript in the `<script>` tags within `index.html` or by creating a separate `script.js` file.
    * Implement a contact form that submits data.
    * Integrate with other services or APIs.

## Contact

For any questions or further information, please contact:

Natthapath Damrongsri
natthapath.d@gmail.com
086 369 3197
