# How to Connect Your Google Sheet to Your Budget Dashboard

This guide walks you through setting up your Google Sheet and publishing it so your Financial Budget Dashboard can automatically read and visualize your financial data in real time.

---

## Step 1: Create or Format Your Google Sheet

1. Open [Google Sheets](https://sheets.google.com) and create a **New Spreadsheet** (e.g., named `My Budget 2026`).
2. Set up row 1 as the header row with the following column names:
   - **Column A**: `Date` (Format: `YYYY-MM-DD` or `MM/DD/YYYY`, e.g., `2026-10-01`)
   - **Column B**: `Description` (e.g., `Apartment Rent`, `Salary`, `Supermarket`)
   - **Column C**: `Category` (e.g., `Housing`, `Groceries`, `Salary`, `Utilities`, `Dining & Entertainment`)
   - **Column D**: `Type` (`Expense` or `Income`)
   - **Column E**: `Amount` (Numeric value, e.g., `1400.00` or `4500.00`)
   - **Column F**: `Notes` (Optional, e.g., `Direct deposit`, `Personal`)
3. Enter your income and expense transactions in rows below.

*(Tip: You can also open the included `budget_template.csv` in Google Sheets via `File` -> `Import` -> `Upload`)*.

---

## Step 2: Publish Your Sheet as CSV (Zero-Backend Live Sync)

Google Sheets provides a built-in feature to publish any sheet as a live CSV feed that any browser or app can read without requiring complicated OAuth credentials or paid servers:

1. In your Google Sheet, click **File** in the top menu.
2. Select **Share** -> **Publish to web**.
3. In the pop-up dialog:
   - In the first dropdown, choose **Sheet1** (or your specific sheet name) rather than "Entire Document".
   - In the second dropdown (which defaults to "Web page"), change it to **Comma-separated values (.csv)**.
4. Click the blue **Publish** button and confirm "OK".
5. Google Sheets will generate a unique link that looks like this:
   ```
   https://docs.google.com/spreadsheets/d/e/2PACX-1vT.../pub?gid=0&single=true&output=csv
   ```
6. Copy this link!

---

## Step 3: Connect to the Dashboard

1. Open your Budget Dashboard in your browser (or on your phone via GitHub Pages).
2. Click the **"Connect Google Sheet"** button (or the Google Sheet icon in the header).
3. Paste your copied CSV URL into the input field.
4. Click **"Sync & Load Data"**.
5. The dashboard will instantly parse your transactions, calculate income, expenses, category spending, 50/30/20 breakdown, and budget health score.
6. The app saves your Sheet URL in your browser's local storage so every time you open the app on your phone, it automatically syncs with your latest Google Sheet entries!
