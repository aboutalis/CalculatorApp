# CalculatorApp

The CalculatorApp is a web-based scientific calculator implemented using HTML, CSS, and JavaScript. It provides a user-friendly interface for performing various mathematical calculations.

## Features

1. Basic arithmetic operations such as addition, subtraction, multiplication, and division.
2. Advanced scientific functions including square root, cube root, power, factorial, exponential, logarithm, trigonometric functions (sine, cosine, tangent), and more.
3. Memory function to store and recall the result of previous calculations using the "Ans" button.
4. Responsive design for seamless usage on different devices such as desktops, tablets, and mobile phones.

## Technologies Used

The project is implemented using the following technologies:

1. HTML (Hypertext Markup Language): Used for creating the structure and layout of the calculator interface. It consists of a `<h1>` heading, a `<div>` container with the class "calculator" that encompasses the calculator elements, and a `<footer>` section for displaying the copyright information.
2. CSS (Cascading Style Sheets): Used for styling the calculator interface and making it visually appealing. It includes styles for the overall layout, buttons, output area, and responsive design for different devices.
3. JavaScript: Used for adding interactivity and implementing the calculator's functionality. Here are the key components and features:

   - Toggle Button: The toggle button with the ID "toggleButton" allows the user to switch between the scientific calculator mode and the simple calculator mode. When clicked, it toggles the visibility of the scientific buttons and updates the text of the `<h1>` heading accordingly.

   - Event Listeners: Event listeners are added to various buttons, including the "=" button and the "Ans" button, to perform specific actions when clicked.

   - Calculation Function: The `calculateResult()` function is called when the "=" button is clicked. It evaluates the mathematical expression entered by the user using the `eval()` function and displays the result in the output area. If an error occurs during the evaluation, the output area displays "Error."

   - Ans Button: The "Ans" button allows the user to recall the result of the previous calculation and include it in the current expression. Clicking the "Ans" button appends its value to the existing expression.

## Usage

1. Open the `index.html` file in a web browser to launch the CalculatorApp.
2. The calculator interface will be displayed, showing a display area for the input and output of calculations.
3. Perform calculations using the provided buttons and functions. The buttons represent numbers, mathematical operations, and scientific functions.
4. To toggle between the scientific calculator mode and the simple calculator mode, click the ">" button. The available scientific functions will be hidden or shown accordingly.
5. The result of each calculation will be displayed in the output area.
6. To perform a new calculation, click the desired buttons to input the expression and click the "=" button to calculate the result.
7. The "Ans" button can be used to recall the result of the previous calculation and include it in the current expression.
8. If an error occurs during the calculation, the output area will display "Error."

Overall, the project provides a user-friendly and functional scientific calculator that can perform a wide range of mathematical calculations. Users can input expressions, toggle between simple and scientific modes, and obtain accurate results displayed in the output area.
