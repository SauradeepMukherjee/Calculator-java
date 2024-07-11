cali Calculator Application
Overview
The cali calculator is a simple Java-based GUI application that provides basic arithmetic operations such as addition, subtraction, multiplication, division, and modulus. The application uses the Swing framework to create a user-friendly interface for performing these calculations.

Features
Basic Arithmetic Operations: The calculator supports addition, subtraction, multiplication, division, and modulus operations.
User-friendly Interface: The GUI is designed with clear and accessible buttons for each number and operation.
Backspace Function: Users can delete the last entered digit.
Clear Function: Users can clear the entire input field.
Decimal Support: The calculator supports decimal numbers for more precise calculations.
Class and Methods
cali Class
The main class for the calculator application. It contains the main method to launch the application and methods to initialize the GUI components.

main(String[] args): The entry point of the application. It invokes the GUI on the Event Dispatch Thread using EventQueue.invokeLater.

cali(): Constructor that calls the initialize() method to set up the GUI.

initialize(): Sets up the JFrame and adds all the necessary buttons and text fields to the frame. It also defines the action listeners for each button to handle user inputs and perform calculations.

GUI Components
JFrame: The main window of the application.
JTextField: A text field to display user input and calculation results.
JButtons: Buttons for digits (0-9), operations (+, -, *, /, %), special functions (C for clear, backspace, and = for equals), and a decimal point (.).
Button Functionality
Number Buttons (0-9): Appends the respective number to the text field.
Decimal Button (.): Appends a decimal point to the text field.
Backspace Button (←): Removes the last character from the text field.
Clear Button (C): Clears the text field.
Operation Buttons (+, -, *, /, %): Stores the first operand and the selected operation, then clears the text field for the second operand.
Equals Button (=): Performs the calculation based on the selected operation and displays the result.
