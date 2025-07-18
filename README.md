Simple Calculator in Java

This is a straightforward command-line calculator application written in Java. It prompts users to input two numbers, select an operation (addition, subtraction, multiplication, or division), displays the result, and allows users to perform multiple calculations until they decide to exit.

Features

    Handles user input robustly, including invalid entries
    Supports basic arithmetic operations
    Prevents division by zero
    Continuous operation until user chooses to exit

How to Use

    Clone or download this repository.
    
    Compile the Java program:
    javac -d . Main.java

      

Run the program:
  
    java org.example.Main

          

  Follow on-screen prompts to enter numbers and select operations.
  Decide whether to perform another calculation or exit.

Code Overview

The main components of the program include:

    Main loop: Keeps the calculator running, allowing multiple calculations.
    Input validation: Ensures users enter valid numbers and choices.
    Operation execution: Performs the selected arithmetic operation with error handling (e.g., division by zero).
    User prompts: Guides users through input and displays results.

Sample Output

          

    Welcome to the Simple Calculator!
    Enter the first number: 10
    Enter the second number: 5
    Select an operation:
    1. Addition (+)
    2. Subtraction (-)
    3. Multiplication (*)
    4. Division (/)
    Enter your choice (1-4): 1
    Result: 10.0 + 5.0 = 15.0
    Do you want to perform another calculation? (yes/no): yes
    Enter the first number: 20
    Enter the second number: 0
    Select an operation:
    1. Addition (+)
    2. Subtraction (-)
    3. Multiplication (*)
    4. Division (/)
    Enter your choice (1-4): 4
    Error: Division by zero is not allowed.
    Do you want to perform another calculation? (yes/no): no
    Thank you for using the calculator. Goodbye!

      

License

This project is for educational purposes. Feel free to customize and extend it as needed.

For any enhancements or issues, please feel free to open an issue or contribute!
