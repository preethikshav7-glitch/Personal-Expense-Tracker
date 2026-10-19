# Personal Expenses Tracker (Java)

A simple console-based Personal Expenses Tracker built with core Java. Record income and expenses, organize them by category, and view summaries to manage your budget.

## Features
- Add income and expenses with category and description
- View all transactions
- Delete a transaction by ID
- View total income, total expenses, and balance
- Category-wise summary
- Monthly report (YYYY-MM)
- Data is saved automatically to `transactions.csv`

## Requirements
- Java JDK 14 or newer

## How to Run
```
javac ExpenseTracker.java
java ExpenseTracker
```

## Menu Options
| Option | Action |
|--------|--------|
| 1 | Add income |
| 2 | Add expense |
| 3 | View all transactions |
| 4 | Delete a transaction |
| 5 | View balance |
| 6 | Category summary |
| 7 | Monthly report |
| 0 | Exit |

## Future Scope
- GUI using Swing or JavaFX
- Database storage (SQLite / MySQL)
- Charts and graphs
- Budget limits and alerts
- Export to Excel
