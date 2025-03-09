# Random Password Generator

This project is a simple web-based random password generator. It allows users to quickly create strong and secure passwords.

## Project Overview

This project consists of an HTML, CSS, and JavaScript implementation of a password generator. The JavaScript code generates a random password based on a predefined set of characters. The user can then copy the generated password to their clipboard.

## project link:https://chilaka-eswari.github.io/Random-Password-Generator/

## Features

* Generates random passwords of a default length (8 characters).
* Includes uppercase and lowercase letters, numbers, and symbols.
* Provides a "Copy to Clipboard" button for easy password retrieval.
* User friendly interface.

## Project Flow

1.  **HTML Structure:**
    * The `index.html` file sets up the basic layout of the password generator.
    * It includes an input field to display the generated password, a "Generate Password" button, and a "Copy to Clipboard" icon.
    * It also links to the css and javascript files.
2.  **CSS Styling:**
    * The `style.css` file provides the visual styling for the password generator.
    * It ensures a clean and user-friendly interface.
3.  **JavaScript Logic:**
    * The `script.js` file contains the JavaScript code that generates the random password.
    * When the "Generate Password" button is clicked:
        * A string of possible characters is defined.
        * A random password of a specified length is generated.
        * The password is displayed in the input field.
    * When the "Copy to Clipboard" icon is clicked:
        * The password in the input field is copied to the user's clipboard.
        * An alert message is displayed to confirm the copy.
        * If no password exists, an alert informs the user to generate one first.

## Technologies Used

* HTML
* CSS
* JavaScript
* Font Awesome (for the clipboard icon)

## How to Use

1.  Clone the repository to your local machine.
2.  Open the `index.html` file in your web browser.
3.  Click the "Generate Password" button to create a random password.
4.  Click the clipboard icon to copy the password to your clipboard.

## Future Improvements

* Allow users to customize the password length.
* Add options to include or exclude specific character types.
* Improve the user interface and responsiveness.
* Add a feature to save generated passwords (with appropriate security measures).
* Add more robust input validation.
