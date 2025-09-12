
ALX Python Introduction Exercises

This repository contains beginner-friendly Python exercises designed to help learners practice basic arithmetic, variables, user input, and simple calculations. Each script is independent and focuses on a specific programming concept.

Scripts Overview
1. Basic Arithmetic Operations

File: basic_operations.py
Purpose: Practice basic arithmetic operations (addition, subtraction, multiplication).

number1 = 10
number2 = 5

addition = number1 + number2
subtraction = number1 - number2
multiplication = number1 * number2

print(f"Addition of {number1} and {number2} is {addition}")
print(f"Subtraction of {number1} and {number2} is {subtraction}")
print(f"Multiplication of {number1} and {number2} is {multiplication}")


Output:

Addition of 10 and 5 is 15
Subtraction of 10 and 5 is 5
Multiplication of 10 and 5 is 50

2. Simple Interest Calculator

File: simple_interest.py
Purpose: Calculate simple interest using the formula I = P * R * T.

principal = 1000
rate = 0.05
time = 3

interest = principal * rate * time

print(f"The simple interest is: {interest}")


Output:

The simple interest is: 150.0

3. Area of a Rectangle

File: rectangle_area.py
Purpose: Calculate the area of a rectangle (Area = length * width).

length = 10
width = 5

area = length * width

print(f"The area of the rectangle is: {area}")


Output:

The area of the rectangle is: 50

4. Convert Hours to Seconds

File: hours_to_seconds.py
Purpose: Convert a given number of hours into seconds.

hours = 2

seconds = hours * 3600

print(f"{hours} hour(s) is {seconds} seconds.")


Output:

2 hour(s) is 7200 seconds.

5. User Input Age Calculator

File: future_age_calculator.py
Purpose: Calculate a user’s age in the year 2050 using input.

current_age = int(input("How old are you? "))
future_age = current_age + 27
print(f"In 2050, you will be {future_age} years old.")


Example Interaction:

How old are you? 30
In 2050, you will be 57 years old.

6. Personal Finance Calculator

File: finance_calculator.py
Purpose: Calculate monthly savings and project annual savings with 5% interest.

monthly_income = float(input("Enter your monthly income: "))
monthly_expenses = float(input("Enter your total monthly expenses: "))

monthly_savings = monthly_income - monthly_expenses
annual_savings = monthly_savings * 12
projected_savings = annual_savings + (annual_savings * 0.05)

print(f"Your monthly savings are ${monthly_savings}.")
print(f"Projected savings after one year, with interest, is: ${projected_savings}.")


Example Interaction:

Enter your monthly income: 5000
Enter your total monthly expenses: 4000
Your monthly savings are $1000.
Projected savings after one year, with interest, is: $12600.0

How to Run the Scripts

Install Python on your system.

Open terminal and navigate to the repository:

cd path/to/alx_be_python/python_introduction


Run any script using:

python script_name.py


Example:

python basic_operations.py

Purpose of the Repository

This repository helps beginners:

Understand Python variables and arithmetic operations

Practice using user input

Apply Python to real-life scenarios (finance, time conversion, calculations)

Build confidence for more advanced Python topics like loops, functions, and data structures

Author

Murad Amin Imer – Aspiring full-stack developer 
