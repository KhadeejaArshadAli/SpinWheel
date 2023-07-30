# SpinWheel

# Description

This is a simple web application that simulates a spinning wheel. When the "Spin" button is clicked, the wheel will start spinning, and after a random rotation, it will stop, displaying a label corresponding to the section of the wheel where the pointer points to.

# How it Works

The application is built using HTML, CSS, and JavaScript. It utilizes the Chart.js library to create a pie chart, which is used to represent the spinning wheel. The `script.js` file contains the custom JavaScript code that handles the spinning animation and displays the result label.

The spinning wheel is divided into multiple sections, each associated with a label. The spinning animation uses the Chart.js library to rotate the pie chart at random angles. When the spinning stops, the JavaScript code calculates the angle at which the pointer points and determines the corresponding label based on the predefined ranges.

# Installation and Usage

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.

Click on the "Spin" button to start the spinning animation. The spinning will stop after a few rotations, and the result label will be displayed below the wheel.

# Configuration

If you want to customize the labels and the number of sections on the wheel, you can modify the `rotationValues` array in the `script.js` file. Each object in the array represents a section on the wheel and contains the following properties:

- `minDegree`: The minimum angle for the section.
- `maxDegree`: The maximum angle for the section.
- `label`: The label to be displayed when the wheel stops at this section.

You can also adjust the `data` and `pieColors` arrays in the `script.js` file to change the size and background color of each section.

# Dependencies

The application uses the following external libraries:

- Chart.js
- chartjs-plugin-datalabels

These libraries are linked via CDNs in the HTML file, so there's no need to install them separately.

# License

This project is licensed under the [MIT License](LICENSE).

Feel free to use, modify, and distribute this code as per the terms of the license.

# Acknowledgments

- The spinning wheel functionality is inspired by various spinning wheel applications and examples found online.

