# elevate-lab-day-1
Explanation:
| Part                              | What It Does                                                   |
| --------------------------------- | -------------------------------------------------------------- |
| `Scanner`                         | Used to take user input from the console.                      |
| Methods (`add`, `subtract`, etc.) | Each performs one math operation.                              |
| `while` loop                      | Keeps the calculator running until the user chooses Exit.      |
| `switch`                          | Decides which operation to perform based on the user’s choice. |
| `Double.NaN`                      | Used when dividing by zero (invalid math).                     |
| `scanner.close()`                 | Closes the input stream safely.                                |

Example Run

Terminal Output Example:
=====================================
     🧮 Java Console Calculator
=====================================

Choose an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
👉 Enter your choice (1-5): 1
Enter first number: 8
Enter second number: 4
Result: 8.0 + 4.0 = 12.0

Choose an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
👉 Enter your choice (1-5): 4
Enter first number: 10
Enter second number: 0
⚠️ Error: Division by zero is not allowed!

Choose an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
👉 Enter your choice (1-5): 3
Enter first number: 6
Enter second number: 7
Result: 6.0 × 7.0 = 42.0

👉 Enter your choice (1-5): 5
✅ Exiting calculator. Goodbye!
