# QR Code Generator

This is a simple web application that generates a QR code based on the text or URL input by the user. The project is implemented using HTML, CSS, and JavaScript.

## Features

- Generate QR codes from text or URLs.
- User-friendly input box with responsive design.
- Animated error feedback for invalid inputs.

## Files

### `index.html`
The main HTML file that contains the structure of the application.

### `style.css`
The CSS file for styling the application.

### `script.js`
The JavaScript file that provides functionality for generating QR codes.

## How to Use

1. Open the `index.html` file in your browser.
2. Enter any text or URL in the input field.
3. Click on the "Generate QR Code" button.
4. The QR code will be displayed below the input box.

## Screenshot
![Screenshot](screenshot.png) *(Add a screenshot of your app here)*

## Code Details

### HTML (`index.html`)
- Includes the input field, button, and an image placeholder for the generated QR code.
- Links the `style.css` file for styling and `script.js` file for functionality.

### CSS (`style.css`)
- Styles the application with a centered container.
- Provides responsive and visually appealing input fields and buttons.
- Adds animations for error handling.

### JavaScript (`script.js`)
- Defines the `generateQR()` function to fetch a QR code from an API and display it.
- Validates user input and adds error animations for empty inputs.

## API Used
This project uses the [QR Code Generator API](https://api.qrserver.com/v1/create-qr-code/) to generate QR codes.

## Setup

1. Clone or download the repository.
2. Open the `index.html` file in your favorite web browser.

## License
This project is open-source and available under the MIT License.
