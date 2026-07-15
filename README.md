# Expense Tracker

A simple command-line Expense Tracker built in **Python** as **Project 2** during the DecodeLabs Python Programming Industrial Training.

## Project Information

- **Project:** Project 2 – Expense Tracker
- **Organization:** DecodeLabs
- **Developer:** Huda Kazmi
- **Language:** Python 3

## Description

This project is a beginner-friendly Expense Tracker that allows users to continuously enter expenses and calculates the total amount spent in real time.

Users can:
- Add expense amounts
- View the running total after each entry
- End the program by typing `quit`
- Prevent invalid inputs using exception handling

The project demonstrates the use of:
- Variables
- Loops
- Conditional Statements
- User Input
- Arithmetic Operations
- Exception Handling (`try` / `except`)

## Features

- Add multiple expenses
- Automatically calculates the running total
- Handles invalid inputs gracefully
- Exit the program by typing `quit`
- Simple command-line interface

## Technologies Used

- Python 3

## Project Structure

```
Expense-Tracker/
│
├── expense_tracker.py
├── README.md
```

## How to Run

1. Make sure Python 3 is installed.
2. Clone this repository:

```bash
git clone https://github.com/your-username/Expense-Tracker.git
```

3. Navigate to the project folder:

```bash
cd Expense-Tracker
```

4. Run the program:

```bash
python expense_tracker.py
```

## Sample Output

```
Expense Tracker
Type quit to stop

Enter expense: 250
Added! Total so far: 250.0

Enter expense: 120.5
Added! Total so far: 370.5

Enter expense: abc
Invalid! Enter a number

Enter expense: quit
Final Total: 370.5
```

## Learning Outcomes

Through this project, I practiced:

- Using variables to store data
- Working with accumulators
- Performing arithmetic operations
- Using `while` loops
- Handling user input
- Implementing exception handling with `try` and `except`
- Building a simple console application

## Future Improvements

Some features that can be added in future versions:

- Categorize expenses
- Save expenses to a file
- Load previous expenses
- Display expense history
- Generate spending reports
- Add monthly budgets
- Display average and highest expense

## Author

**Huda Kazmi**

Project completed as part of the **DecodeLabs Python Programming Industrial Training**.
