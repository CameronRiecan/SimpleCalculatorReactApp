# Simplest Working Calculator

The "Simplest Working Calculator" is a straightforward React application that allows users to perform basic mathematical operations such as addition, subtraction, multiplication, and division. It's designed to demonstrate the fundamental concepts of React state management and event handling.

## Features

- Addition: Add two numbers and display the result.
- Subtraction: Subtract one number from another and display the result.
- Multiplication: Multiply two numbers and display the result.
- Division: Divide one number by another and display the result.
- Reset Input: Clear the input field for new calculations.
- Reset Result: Reset the result to zero.

## How It Works

This calculator uses React to manage the user interface and perform calculations. Here's a brief overview of how it functions:

- The application maintains two references: `inputRef` for the input field and `resultRef` for displaying the result.
- The `useState` hook is used to manage the current result, initialized to 0.
- Four functions (`plus`, `minus`, `times`, `divide`) are defined to handle each operation.
- Each function updates the result based on the user's input from the input field.
- The "Reset Input" button clears the input field, allowing the user to enter new values.
- The "Reset Result" button resets the result to zero.

### Usage

1. Clone this repository to your local machine.
2. Run `npm install` to install the necessary dependencies.
3. Start the application with `npm start`.
4. Open the app in your browser and use the buttons to perform calculations.
5. Click "Reset Input" to clear the input field for new calculations.
6. Click "Reset Result" to reset the result to zero.

Feel free to explore the code to understand how React state and event handling are used to create this simple calculator.

## Project Structure

- `App.js`: The main React component containing the calculator logic.
- `App.css`: CSS styling for the calculator.
- `index.js`: The entry point of the React application.
- `public/`: Public assets and HTML template.

## Credits

This project is a simplified example for educational purposes and was created by Cameron Riecan.
