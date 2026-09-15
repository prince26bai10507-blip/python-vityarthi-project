# Statement of the Project: Expense Tracker (Python CLI)
# 1. Project Title

Simple Command-Line Expense Tracker

# 2. Problem Statement

Managing daily expenses can become difficult without a proper system to record and track spending. People often forget small purchases or lose track of how much they have spent over time.
There is a need for a simple tool that allows users to:

Record expenses easily

Categorize their spending

Review past expenses

Know the total amount spent at any time

This project aims to solve this problem using a command-line based expense management system.

# 3. Objective

The objective of this project is to design and implement a basic expense tracker in Python that allows users to:

Add individual expenses

View all recorded expenses

Calculate the total amount spent

Interact with the system through a simple menu-driven interface

# 4. Scope of the Project

The application runs in the terminal/command line.

Expenses are stored temporarily in memory using a Python list (no database).

Each expense contains:

Amount

Category

Note

The program runs in a continuous loop until the user chooses to exit.

# 5. Methodology

The system uses three main functions:

add_expense()
Takes user input for amount, category, and note, then stores the expense in a list.

view_expenses()
Displays all existing expenses in a numbered format.

total_spent()
Sums all expense amounts and displays the total.

A while True loop displays a menu for user interaction and calls the appropriate function based on the user's choice.

# 6. Expected Output

Users can successfully record expenses.

Users can view the list of all recorded expenses.

Users can see the total money spent.

The program provides clear messages and feedback (e.g., “Expense added!”, “No expenses yet.”).

# 7. Limitations

Data is not stored permanently — all expenses reset when the program stops.

Only numeric input is accepted for amount.

No error handling for invalid inputs (beyond simple checks).

# 8. Conclusion

This project provides a simple and effective solution to manage daily expenses using Python. It demonstrates the use of lists, functions, loops, and basic user interaction.
Although basic, the program can be expanded with more features such as data storage, reporting, and input validation.
