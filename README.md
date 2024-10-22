# Expense Tracker

A simple expense tracker application to manage and visualize your income and expenses. Users can add, delete transactions, and see a breakdown of their financial data with charts.

## Features

- **Track Income & Expenses:** Easily add income and expenses to the app to keep track of your finances.
- **Calculate Total Balance:** The app will automatically calculate your total balance by summing all your transactions.
- **Add/Delete/Edit Transactions:** You can add, edit and remove transactions (income or expenses) with specific categories.
- **Data Visualization:** Visualize your financial data through pie charts for better insights.

## Learning Points

- **Handling User Input:**
  - Forms are used to input transactions (income/expense) and update the list of transactions dynamically.
  
- **useState & useEffect:**
  - `useState` is used to manage the application's state (balance, transactions).
  - `useEffect` ensures that changes in state (such as new transactions) are reflected in the displayed financial data.

- **Integration of a Charting Library:**
  - Data is visualized using a charting library, using [Chart.js](https://www.chartjs.org/), for clear, visual representation of income and expenses.
  
## Tech Stack

- **React:** For building the user interface.
- **Chart.js :** For visualizing the financial data with different chart types (Bar, Pie, etc.).
- **CSS/Styled Components:** For styling the application.
