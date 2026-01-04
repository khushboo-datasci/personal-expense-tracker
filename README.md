# Personal Expense Tracker
A command-line based Python application to securely record, manage, and analyze daily expenses with multi-user support.

---

## Project Overview
The Personal Expense Tracker is a Python application that allows users to:

- Sign up and log in securely
- Add daily expenses with details: date, category, description, amount
- View all expenses in a tabular format
- Delete incorrect or unwanted entries
- Filter expenses by category
- Generate monthly summaries
- Update username and password without losing data

It demonstrates practical usage of Python fundamentals, data handling with Pandas, file-based persistence using CSV files, and secure multi-user support.

---

## Problem Statement
Many individuals struggle to track their daily or monthly spending. Manual tracking is inefficient, error-prone, and lacks accountability. Users may also forget credentials or share accounts, leading to data loss.  

This project provides a secure, automated, and structured system for personalized expense management.

---

## Objectives
- Create secure accounts (Sign Up / Login)
- Add daily expenses with relevant details
- View, delete, and filter expense records
- Generate monthly summaries for budgeting
- Maintain per-user CSV storage for persistent data
- Update username and password safely without losing data

---

## Technologies Used
- **Python** – Core programming  
- **Pandas** – Data handling and analysis  
- **Tabulate** – Pretty printing tables in CLI  
- **CSV** – File-based persistent storage  
- **JSON** – User credentials and authentication  

---

## Features
- Multi-user login and sign up
- Add, view, delete, and filter expenses
- Monthly expense summaries
- Update username and password
- Graceful program exit with data safety

---

## Demo

![Login Screen](images/Screenshot 2026-01-04 9.06.44 PM.png)
![Dashboard / Expenses](images/Screenshot 2026-01-04 9.07.15 PM.png)


---

## Installation / Setup
1. Clone the repository:
```bash
git clone  [https://github.com/khushboo-datasci/personal-expense-tracker/blob/main/personal_expense_tracker.py]

2.Navigate to the project folder:

 cd PersonalExpenseTracker

3.Install required libraries:
  pip install pandas tabulate

4.Run the project:
  main()

5.Usage

Login or Sign Up

Use the menu to add, view, delete, or filter expenses

Generate monthly summaries

Update account credentials if needed

Exit program safely

Step-by-Step Flow

Sign Up / Login system – Secure multi-user authentication

Load or Create User CSV – Persistent storage for user expenses

Add Expense – Record new expenses with date, category, description, and amount

View Expenses – Display all expenses in a clean table

Delete Expense – Remove incorrect or unwanted entries

Filter by Category – Analyze expenses based on category

Monthly Summary – Generate monthly spending reports

Update Username or Password – Change credentials safely

Exit – Graceful program termination

Author

Khushboo Singh
GitHub Profile


---

### **Step 6: Next actions for you**
1. Create `images/` folder in your repo root.
2. Paste your screenshots in that folder (rename: `login.png`, `dashboard.png`, `monthly_summary.png`).
3. Save this as `README.md` in repo root.
4. Push everything to GitHub:
```bash
git add .
git commit -m "Add final README with screenshots"
git push




















b.com/yourusername/PersonalExpenseTracker.git
