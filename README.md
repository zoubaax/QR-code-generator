

# QR Code Generator with Node.js

![QR Code Generator](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![QR Code](https://img.shields.io/badge/QR-Code-brightgreen)

A command-line QR code generator built with Node.js that:
- Generates QR codes from text/URLs
- Saves the QR code as a PNG image
- Stores the input text/URL in a text file

## Features

- Generate QR codes from user input
- Save QR code as `qr-code.png`
- Save input text/URL as `user-input.txt`
- Simple command-line interface
- Lightweight and easy to use

## Prerequisites

- Node.js (v14 or higher recommended)
- npm (comes with Node.js)

## Installation

1. Clone this repository or download the project files
2. Navigate to the project directory in your terminal
3. Install the required dependencies:

```bash
npm install inquirer qr-image
```

## Usage

Run the application with:

```bash
node index.js
```

Follow the prompts to:
1. Enter the text or URL you want to encode
2. The application will:
   - Generate a QR code (`qr-code.png`)
   - Save your input text (`user-input.txt`)

## Project Structure

```
qr-code-generator/
├── index.js        # Main application file
├── qr-code.png     # Generated QR code (created after first run)
├── user-input.txt  # Saved user input (created after first run)
├── package.json    # Project configuration
└── README.md       # This file
```

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer) - For interactive command-line prompts
- [qr-image](https://www.npmjs.com/package/qr-image) - For generating QR code images
- Built-in `fs` module - For file system operations

## Type Module

This project uses ES modules (set in package.json with `"type": "module"`) instead of CommonJS.

## License

This project is open source and available under the [MIT License](LICENSE).

