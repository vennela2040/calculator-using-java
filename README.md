
Title:Simple Calculator in Java Swing
------------------------------------------------------------------------------
InternInfo
NAME:vennela kudumula 
Date:25-4-2024
ID:ICOD7046
------------------------------------------------------------------------------
Introduction
This project implements a simple calculator using Java Swing, a GUI toolkit for Java. The calculator provides basic arithmetic operations such as addition, subtraction, multiplication, and division. It also includes additional functionalities like decimal point, clear, delete, and negation. The user interface consists of a text field to display the input and output, along with buttons for numeric input and operations.
------------------------------------------------------------------------------
Implementation
Technologies Used
- Java
- Java Swing
------------------------------------------------------------------------------
Features
1.User Interface: The calculator has a simple GUI consisting of a JTextField to display the input and output, and JButtons for numeric input and operations.
2.Arithmetic Operations: Supports basic arithmetic operations including addition, subtraction, multiplication, and division.
3.Additional Functionalities: Includes buttons for decimal point, clear (Clr), delete (Del), and negation (-).
4.Dynamic Input Handling: Dynamically updates the text field based on user input and performs arithmetic calculations.
------------------------------------------------------------------------------

Limitations
- The calculator does not handle errors or exceptions, such as division by zero or invalid input.
- The calculator supports only basic arithmetic operations and lacks advanced functionalities like parentheses or memory operations.
------------------------------------------------------------------------------
Code Explanation
Class Structure
- Calculator:Implements ActionListener to handle button click events and represents the main calculator application.

Fields
- JFrame frame: Main frame to hold the GUI components.
- JTextField textfield: Displays the input and output.
- JButton[] numberButtons: Array of buttons for numeric input (0-9).
- JButton[] functionButtons: Array of buttons for arithmetic operations and additional functionalities.
- JPanel panel: Panel to organize the numeric and function buttons.
- Font myFont: Custom font for the buttons and text field.
- double num1, num2, result: Variables to store the operands and result.
- char operator: Variable to store the arithmetic operator.

Constructors
- Calculator(): Initializes the JFrame, JTextField, JButtons, and JPanel. Sets up the GUI layout and adds action listeners to the buttons.

Methods
- actionPerformed(ActionEvent e): Handles the button click events and performs corresponding actions based on the button clicked.

Event Handling
- Handles button click events for numeric input, arithmetic operations, decimal point, clear, delete, and negation.
- Dynamically updates the text field based on user input and performs arithmetic calculations when the equals (=) button is clicked.

GUI Configuration
- Configures the JFrame size, layout, and properties.
- Sets the font, size, and properties for the JTextField and JButtons.
- Organizes the numeric and function buttons in a GridLayout within a JPanel.

------------------------------------------------------------------------------
Conclusion
The Simple Calculator in Java Swing provides a basic calculator experience for users, allowing them to perform arithmetic operations and additional functionalities with a simple and intuitive interface. While it covers essential arithmetic operations and provides additional functionalities like decimal point and negation, it lacks error handling and advanced features found in scientific or advanced calculators. Future improvements could include adding error handling, supporting more advanced operations, and enhancing the user interface for a more polished and user-friendly experience. Overall, this project serves as a foundational example of implementing a calculator using Java Swing, which can be extended and improved upon for more advanced applications.
