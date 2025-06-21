# 💰 Bank Misr – Loan Payment Calculator (Tkinter GUI)

## 📌 Project Overview

This project was developed as a final project during my second year (Fall semester) as part of my academic work at BIS (Business Information Systems) University. It simulates a basic **Loan Payment Planning System** for Bank Misr using **Python and Tkinter GUI**.

Users can select a job role, input a loan amount, and select a repayment duration. The system calculates the **total interest**, **total loan**, and **monthly payment** based on a fixed interest rate table.

---

## 🖥️ Features

- 🧮 **Loan Calculation Based on Years**:
  - Calculates interest for 1, 3, 5, or 7 years
  - Applies different fixed interest rates for each term
- 🧾 **Monthly Payment Breakdown**:
  - Displays total interest, final loan amount, and monthly installment
- ✅ **Input Validation**:
  - Ensures loan amount and duration are positive and valid
- 🧼 **Clear & Exit Functions**:
  - Allows users to reset the form or exit the app
- 🎨 **Graphical User Interface (GUI)**:
  - Developed with Tkinter, including drop-down menus, buttons, and a logo image

---

## 🧠 Concepts Applied

- ✅ GUI Programming using `Tkinter`
- ✅ Real-time error handling with `try-except` and `messagebox`
- ✅ Loan and interest calculation formulas
- ✅ Input validation and feedback
- ✅ Clean layout with form inputs, labels, and visual results

---

## 📊 Interest Rate Table

| Years | Interest Rate (%) |
|-------|-------------------|
| 1     | 13.76             |
| 3     | 14.06             |
| 5     | 14.87             |
| 7     | 15.71             |

---

## 🔧 How to Run

1. Ensure you have Python 3.x installed.
2. Save the logo image as `bmp-logo.png` in the same folder as the script.
3. Run the script:
   ```bash
   python loan_calculator.py
