# Infinite Slider Effect with Interactive Description

This repository contains the source code for a dynamic content slider with an infinite scrolling effect and an interactive description. The slider allows users to navigate through a series of elements (generic examples like "Object 1," "Object 2," etc., but easily customizable) and displays a detailed description of the currently centered element.

## Key Features

* **Infinite Slider:** Implements a carousel of elements that scrolls continuously, creating the illusion of infinite scrolling to the left or right.
* **Dynamic Elements:** The slider elements (name and description) are generated dynamically from a JavaScript data file (`slider-data.js`), making it easy to add or modify content.
* **Interactive Description:** When an element is centered in the slider, its corresponding description is shown in a designated area, providing additional information to the user.
* **Responsive Design:** The slider's design adapts to different screen sizes, ensuring an optimal user experience on mobile and desktop devices.
* **Navigation Controls:** Includes "left" and "right" buttons to allow users to navigate the slider manually.
* **Modular Code:** The code is organized into separate files for HTML, CSS (general styles and slider-specific styles), and JavaScript (slider logic and data), facilitating maintenance and scalability.

## Included Files

* `index.html`: The main HTML structure of the page, containing the slider, navigation buttons, and description area.
* `index.css`: General CSS styles for the page, including layout, colors, and typography.
* `slider.css`: Specific CSS styles for the slider, controlling the design, animation, and behavior of the slider elements.
* `slider.js`: JavaScript code that implements the slider logic, including scrolling, description updating, and button event handling.
* `slider-data.js`: JavaScript file containing the data for the slider elements (name and description). This file can be modified to integrate custom content.

## Usage

1.  Clone the repository.
2.  Open the `index.html` file in a web browser.
3.  Navigate the slider using the "left" and "right" buttons.
4.  Modify the `slider-data.js` file to customize the slider content.
5.  (Optional) Adjust the styles in `index.css` and `slider.css` to adapt the design to your needs.

## Technologies

* HTML
* CSS
* JavaScript (ES Modules)

## Credits

(You can add your name or any other relevant credits here)