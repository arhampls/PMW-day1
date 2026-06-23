# Simple Python Calculator

This directory contains a basic command-line calculator written in Python (`script.py`).

## ⚙️ Functions Supported
The calculator currently supports four fundamental arithmetic operations:
1. **Addition (+)**: Adds two numbers together.
2. **Subtraction (-)**: Subtracts the second number from the first.
3. **Multiplication (*)**: Multiplies two numbers.
4. **Division (/)**: Divides the first number by the second. (Includes built-in protection against dividing by zero).

## 🚀 How to Use It
1. Open your terminal, command prompt, or PowerShell.
2. Navigate to the folder containing `script.py`.
3. Run the script using Python:
   ```bash
   python script.py
   ```
4. The program will present a menu. Type the number corresponding to the operation you want to perform (e.g., `1` for Addition) and press **Enter**.
5. When prompted, type your first number and press **Enter**.
6. Type your second number and press **Enter**.
7. To exit the calculator at any time, type `q` at the main menu prompt.

## 📊 Expected Result
After entering your numbers, the calculator will compute the math and output the full equation along with the result. It will then loop back to the main menu so you can perform another calculation.

**Example output for Addition:**
```text
Welcome to the Simple Python Calculator!
Select an operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4) or 'q' to quit: 1
Enter first number: 15.5
Enter second number: 4.5
Result: 15.5 + 4.5 = 20.0
------------------------------
```

**Example output for an Error:**
```text
Enter choice (1/2/3/4) or 'q' to quit: 4
Enter first number: 10
Enter second number: 0
Result: 10.0 / 0.0 = Error! Division by zero.
------------------------------
```
