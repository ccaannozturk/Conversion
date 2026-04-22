# Advanced FX & Interest Calculator 💱📈

A sophisticated, single-page personal finance utility designed to analyze credit card debt payments, forecast EUR to TRY currency conversions, and calculate investment breakeven points. It integrates real-time exchange rates and historical charting to empower data-driven financial decisions.

## 🎯 Purpose

This tool was built to solve a specific personal finance challenge: optimizing international money transfers (EUR to TRY) to cover credit card debts while maximizing potential interest yields. It helps answer the ultimate question: *"Should I pay the full debt or the minimum, and how does the exchange rate and local interest rate affect my net worth?"*

## ✨ Key Features

* **💳 Payment Strategy Planner:** Calculate total household credit card payable amounts and instantly determine the 40% minimum payment threshold.
* **💱 Live & Manual FX Conversion:** Fetches real-time EUR/TRY exchange rates via the [Frankfurter API](https://www.frankfurter.app/), with the option to input manual rates for "what-if" scenarios.
* **📈 Advanced Interest & Breakeven Analysis:** * Calculates Simple and Compound interest over a selected investment period.
  * Factors in the 15% withholding tax automatically.
  * Determines the **Breakeven FX Rate** (the future exchange rate required to match the total value of converting today plus earning interest).
  * Performs **Reverse Breakeven Analysis** to see how long an investment must be held to beat a hypothetical future exchange rate.
* **📊 Historical Charting:** Visualizes the last 30 days of the EUR/TRY exchange rate using `Chart.js`.
* **💾 Scenario Comparison:** Save multiple conversion/interest scenarios to a local table for quick side-by-side comparison.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (Utility-first styling)
* **Charting:** Chart.js (Interactive data visualization)
* **External APIs:** Frankfurter API (Open-source, European Central Bank exchange rates)

## 🚀 How to Run Locally

This is a completely client-side application. No servers, no build steps, and no dependencies to install.

1. Clone the repository:
   ```bash
   git clone [https://github.com/ccaannozturk/advanced-fx-calculator.git](https://github.com/ccaannozturk/advanced-fx-calculator.git)
