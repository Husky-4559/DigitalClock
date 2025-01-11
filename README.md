# Digital Clock Application

This is a simple digital clock application built using HTML, CSS, and JavaScript. It displays the current time in a user-friendly format, including hours, minutes, seconds, and AM/PM.

## Features

• Displays the current time in a 12-hour format.
• Dynamically updates every second.
• Stylish design with a gradient background and elegant fonts.
• Responsive layout centered on the page.

## File Structure

• index.html: The main HTML file that defines the structure of the clock.
• styles.css: The CSS file that styles the clock and the page layout.
• script.js: The JavaScript file that handles the dynamic time updates.

## How It Works

1. HTML Structure:
   • The index.html file contains a div with the class clock.
   • The clock has separate span elements for hours, minutes, seconds, and AM/PM.
2. CSS Styling:
   • The styles.css file applies a linear gradient background and a clean typography style using Google Fonts.
   • The clock is styled to display time prominently in the center of the screen.
3. JavaScript Functionality:
   • The script.js file defines a function updateTime() that calculates the current time using the Date object.
   • The time is formatted into a 12-hour format, padded with leading zeros for single-digit values.
   • The DOM is updated every second using setInterval().

## How to Use

1. Download the project files (index.html, styles.css, and script.js).
2. Open the index.html file in any modern web browser.
3. The clock will display the current time and update automatically.

## Example Output

The clock will appear in the center of the screen, displaying something like:

12 : 45 : 30 PM

## Technologies Used

• HTML5: For the structure of the application.
• CSS3: For the design and layout of the application.
• JavaScript (ES6): For dynamically updating the time.
