Project-summary

# Calculator- Project plan
Task 1: Create a repository and add the program files. 
Project-summary
Task 2: Import the required libraries. 
Task 3: Define the calculator() function.
Task 4: Create the GUI window with the title and create the buttons. 
Task 5: Implement the functionality of the buttons to perform specific operations. 
Task 6: Implement error handling for invalid inputs or operations.
Task 7: Define the format_history() and save the calculation history to display the previous operations for future reference. 
Task 8: Display the result on the GUI window.

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

