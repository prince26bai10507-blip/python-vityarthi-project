# 🧾 Expense Tracker (Python CLI)

A simple command-line Expense Tracker written in Python.
This program allows users to add expenses, view all recorded expenses, and calculate the total amount spent.

# 🚀 Features

Add Expense
Enter the amount, category, and an optional note.

View Expenses
Displays all saved expenses in a clean numbered format.

Total Spent
Calculates and displays the sum of all expense amounts.

Interactive Menu
Runs in a loop until the user chooses to exit.

# 📌 How It Works
Main Menu
1. Add Expense
2. View Expenses
3. Total Spent
4. Exit

Add Expense

The program asks for:

Amount (integer)

Category (e.g., food, travel, shopping)

Note (optional description)

View Expenses

Displays all expenses in this format:

1 ₹ 200 | amount: 200 | Food | Lunch

Total Spent

Shows the total of all amount values entered.

# 📂 Code Structure

add_expense() → Adds a new expense to the list

view_expenses() → Prints all expenses

total_spent() → Shows the sum of money spent

A main loop provides menu-based navigation

# ▶️ Running the Program

Copy the code into a expense_tracker.py file.

Run it using:

python expense_tracker.py


Follow the on-screen menu to add or view expenses.

# 🛠 Future Improvements (Optional Ideas)

Save expenses to a file (JSON/CSV)

Load expenses when the program starts

Add date/time automatically

Export summary reports

Add input validation for non-numeric amounts
