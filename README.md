This code is a simple console-based calculator program that performs basic arithmetic operations: addition, subtraction, multiplication, and division. It continuously prompts the user for input until the user decides to exit. Here's a breakdown of how the code works:

    Functions Definition:
        addition(n1, n2): Takes two numbers as input and returns their sum, formatted as a string.
        subtraction(n1, n2): Takes two numbers as input and returns their difference. If the first number is less than the second, it returns the absolute difference (subtracts the larger number from the smaller one).
        multiplication(n1, n2): Takes two numbers as input and returns their product, formatted as a string.
        division(n1, n2): Takes two numbers as input and performs division. If the second number is zero, it returns an error message "Invalid: Division by zero". Otherwise, it returns the result of the division.

    User Interaction:
        The program displays a menu with five options: addition, subtraction, multiplication, division, and exit.
        The user selects an option by entering a number (1 to 5).
        The user is then prompted to enter two numbers.

    Processing the User Choice:
        Based on the user's choice, the corresponding function (addition, subtraction, multiplication, division) is called with the user-provided numbers.
        The result of the operation is printed to the console.
        If the user chooses option 5, the program exits the loop and terminates.

    Loop Structure:
        The program runs in a while True loop, which means it will keep executing until the user chooses to exit (option 5).
