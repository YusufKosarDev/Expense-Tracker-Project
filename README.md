# 💰 Expense Tracker Project

A clean, single-page Expense Tracker application that allows users to track their income and expenses with real-time balance updates.

## 📝 What Does It Do?

The app helps users manage personal finances by analyzing transactions entered by the user and updating values instantly:

Balance: Total balance calculated from all transactions

Income: Sum of all positive amounts

Expenses: Sum of all negative amounts

Transaction List: Displays all added transactions with delete functionality

All data is stored locally in the browser using LocalStorage, so it persists after page refresh.

## ⚙️ How Does It Work?

Single-page structure:
HTML handles the structure, CSS the styling, and JavaScript the logic.

Event-driven logic:
A submit event listener on the form captures user input and adds new transactions.

Data persistence:
Transactions are saved and retrieved from localStorage.

Real-time calculations:
Balance, income, and expense totals are recalculated using Array.filter() and Array.reduce() on every update.

Dynamic DOM updates:
The transaction list is rebuilt dynamically, and transactions can be removed instantly.

Currency formatting:
Uses Intl.NumberFormat for proper USD currency formatting.

## 🎓 What I Learned?

Managing application state with arrays and LocalStorage

Using array methods (map, filter, reduce) for real-time calculations

DOM manipulation and dynamic list rendering

Handling form input and preventing default browser behavior

Creating a responsive and modern UI with CSS Grid & Flexbox

Structuring a small but complete front-end project

### 🚀Live Demo: https://yusufkosardev.github.io/Expense-Tracker-Project/
