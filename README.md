# 💰 Expense Tracker (Tkinter + JSON + Excel)

This is a **Python desktop application** built with **Tkinter** that allows users to track daily expenses, save them in both JSON and Excel formats, and visualize monthly summaries with pie charts. It's beginner-friendly, useful, and easily extensible.

---

## ✅ Features

### 1. Add Expense
- Enter amount, category, and optional date.
- If no date is given, today's date is used.
- The expense is saved to:
  - A **JSON file (`expenses.json`)** for internal tracking.
  - An **Excel file (`expenses.xlsx`)** for exporting/sharing.

### 2. View All Expenses
- Displays all recorded expenses in a pop-up window.
- Format: `₹Amount | Category | Date`.

### 3. Monthly Summary with Chart
- User inputs month and year.
- App filters and sums expenses by category for that month.
- Displays:
  - Text summary of totals by category.
  - A **pie chart** using `matplotlib`.

### 4. GUI Interface
- Built with `tkinter`.
- Clean, user-friendly layout with labeled input fields and buttons.

---

## 📦 File Structure

