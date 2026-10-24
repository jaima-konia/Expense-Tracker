# Expense Tracker 💰

A simple and interactive Expense Tracker built with **HTML, CSS, and JavaScript**. This project helps users track their income and expenses, calculate their current balance, and keep transaction records saved in the browser.

## ✨ Features

- **Add Transactions:** Add income or expenses with a description and amount.
- **Balance Summary:** Automatically calculates the total balance, income, and expenses.
- **Transaction History:** Displays transactions with the most recently added transaction at the top.
- **Delete Transactions:** Remove individual transactions from the history.
- **Local Storage:** Saves transactions in the browser so they remain available after refreshing the page.
- **Currency Formatting:** Displays amounts in US dollar (USD) format.
- **Dynamic Styling:** Uses different CSS classes to distinguish income from expenses.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Browser Local Storage API

## ⚙️ How It Works

1. Users enter a transaction description and amount.
2. JavaScript stores the transaction in an array.
3. The application updates the transaction list and financial summary.
4. Transactions are saved in `localStorage` using `JSON.stringify()`.
5. When the page loads, saved transactions are retrieved using `JSON.parse()`.
6. Users can delete transactions, and the balance and summary update automatically.

**Note:** Enter positive amounts for income and negative amounts for expenses.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in your web browser.
4. Start adding your income and expenses.

No additional installation or dependencies are required.

## 📚 What I Learned

While building this project, I practiced:

- Selecting and manipulating DOM elements.
- Handling form submissions and preventing default behavior.
- Working with arrays and objects.
- Using array methods such as `push()`, `filter()`, `reduce()`, and `reverse()`.
- Dynamically creating and removing HTML elements.
- Storing and retrieving data with `localStorage`.
- Formatting currency with the `Intl.NumberFormat` API.
- Updating the UI whenever application data changes.

Live demo: https://jaima-konia.github.io/Expense-Tracker/

## Screenshoot
<img width="1913" height="909" alt="image" src="https://github.com/user-attachments/assets/dd5e85bf-f87c-4505-bb96-9523c68fb778" />


---

If you find this project useful, feel free to explore the code and suggest improvements!
