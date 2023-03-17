Project-summary

# Calculator- Project plan
Task 1: Create a repository and add the program files. 
Task 2: Design a Graphical User Interface screen with the appropriate background color and layout. 
Task 3: Add an introduction to the calculator. 
Task 4: Create input for variables and operators. 
Task 5: Create buttons for numbers and operators. 
Task6:Implement the functionality of the buttons to perform arithmetic and trigonometric operations. 
Task 7: Display the results after the operation on the GUI screen. 
Task 8: Add access to the cancel and clear buttons to reset the input and results. 
Task 9: Implement error handling for invalid inputs or operations. 
Task 10: Implement keyboard support for input fields and buttons. 
Task 11: Add a theme functionality to the calculator to customize the GUI. 
Task 12: Save the calculation history to display the previous operations for future reference.

main
The GUI-based Calculator will be developed using Python script. The Calculator has basic arithmetic operations, trigonometric functions, power, and square root. It also keeps track of users' previous operations and lets them view their history.

The format_history() function takes a list of previous operations and returns a formatted string with the last four operations.

The calculator() function sets up the GUI layout and runs the event loop. The event loop handles user input and updates the display accordingly. The prev_results list keeps track of the user's previous expressions, displayed in the history popup when you click the History button.

The Calculator supports the following operations:
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Square root (sqrt)
Power (pow)
Trigonometric functions (sin, cos, and tan)

The Calculator uses the eval() function to evaluate the user's input as a mathematical expression. If an error occurs during evaluation, such as a division by zero or an invalid expression, the Calculator displays an error message as Expression Error.

If any invalid entry occurs, the user can click the X button to delete the expression backward.
To clear the operation, the user can click the C button.
To exit the Calculator, the user can click the Cancel button or close the window.


Python Calculator is a user friendly software 
