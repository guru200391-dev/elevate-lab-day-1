# elevate-lab-day-1
Step-by-Step: Setting up Java in VS Code
🪜 Step 1: Install Java JDK

The JDK (Java Development Kit) is the first thing you need before using VS Code for Java.

Go to 👉 https://www.oracle.com/java/technologies/downloads/

Download the latest Java SE Development Kit (JDK) for your operating system (e.g., Windows x64 Installer).

Run the installer → keep default options → click Next until it finishes.

Verify installation:

Open Command Prompt (cmd)

Type:
java -version
javac -version
If both show version numbers, your JDK is installed correctly ✅

🪜 Step 2: Install VS Code

Go to 👉 https://code.visualstudio.com/

Download and install Visual Studio Code (Windows / Mac / Linux).

After installation, open VS Code.

🪜 Step 3: Install Java Extensions in VS Code

To make VS Code understand and run Java:

Open VS Code → click on the Extensions icon on the left sidebar (or press Ctrl + Shift + X).

In the search bar, type:

Extension Pack for Java


Click Install on the official pack from Microsoft.

This pack includes:

Language Support for Java

Debugger for Java

Test Runner for Java

Maven & Project Manager for Java

✅ These tools allow you to run, debug, and manage Java projects easily.

🪜 Step 4: Set Up Your First Java Program

Create a new folder on your computer (e.g., C:\Users\YourName\JavaPrograms).

Open that folder in VS Code (File → Open Folder).

Create a new file → name it Calculator.java.

Paste this simple test code:

public class Calculator {
    public static void main(String[] args) {
        System.out.println("Java setup successful!");
    }
}


Save the file (Ctrl + S).

🪜 Step 5: Run the Program

You have two options:

Option 1 – Using Run Button

At the top-right of VS Code, click Run ▶️.

Output will appear in the Terminal panel below:

Java setup successful!


Option 2 – Using Terminal manually

Open VS Code’s terminal (Ctrl + ~)

Compile:

javac Calculator.java


Run:

java Calculator


Output:

Java setup successful!

🪜 Step 6: Done!

✅ You now have:

JDK installed

VS Code with Java extensions

Java environment ready to write and run programs

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
