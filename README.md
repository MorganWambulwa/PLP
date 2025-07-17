 What This Project Does
This calculator:

Prompts the user to enter two numbers

Calculates the:

✅ Sum

✅ Difference

✅ Product

✅ Quotient

Displays the results in a clean, readable format

Perfect for beginners learning Python basics and input/output operations!

📌 Features
Handles float inputs to support decimals

Clean and easy-to-read Python code

Lighthearted and beginner-friendly comments

🧠 How It Works
python
Copy code
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2

print(f"Sum: {sum_result}")
print(f"Difference: {difference_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")
Note: The script assumes the second number is not zero, so division works without crashing.

✅ Requirements
Python 3.x
(Tested on Python 3.8+)

💡 How to Run
Open your terminal or command prompt.

Navigate to the folder containing the script.

Run the script:

bash
Copy code
python fun_calculator.py
Follow the prompts to enter two numbers.

Get your results instantly!

🤝 Contributing
Feel free to fork the repo and add features like:

Error handling for division by zero

Option to run multiple calculations

A graphical user interface (GUI) using Tkinter or PyQt
