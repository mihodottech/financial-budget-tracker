# Financial Budget Tracker & Analytics Dashboard
### Connected to Google Sheets | Accessible on Mobile via GitHub Pages

A modern, responsive, mobile-first financial dashboard built to connect directly to your Google Sheet so you can understand your budget, track expenses, visualize trends, and check your financial health on your phone or computer.

---

## Features

- **Google Sheets Real-time Sync**: Connects via published Google Sheets CSV URL with zero server requirements.
- **Mobile-First Responsive UI**: Clean cards, responsive navigation, touch-friendly buttons, and dark-accent modern design.
- **Financial KPI Cards**: Instant breakdown of Total Income, Total Expenses, Net Savings, Savings Rate, and Budget Health Score.
- **Category Budgets & Progress Bars**: Set spending limits per category and track remaining balances with colored alert thresholds (Safe, Warning, Over Budget).
- **Interactive Visualizations**:
  - Donut chart of expenses by category
  - Income vs Expense monthly cash flow bar & trend chart
  - Planned Budget vs Actual Spending comparison
  - 50/30/20 Rule budget distribution (Needs, Wants, Savings/Debt)
- **Transaction Explorer**: Search, filter by category or type, sort by date or amount.
- **Add / Edit / Export**: Log transactions locally and export back to CSV.
- **Smart Insights**: Dynamic financial tips highlighting high-spend categories, savings rates, and budget recommendations.

---

## How to Set Up in Visual Studio / VS Code & Host on GitHub for Your Phone

### Step 1: Open in Visual Studio / VS Code
1. Place this project folder (`financial-budget-tracker`) on your computer.
2. In **Visual Studio** or **VS Code**, select **File -> Open Folder...** and choose this directory.
3. If using VS Code, install the extension **Live Server** (by Ritwick Dey) to preview locally by right-clicking `index.html` -> **Open with Live Server**.

---

### Step 2: Push to GitHub
1. Open your terminal in VS Code (or Git Bash / Command Prompt in this folder):
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Budget Tracker"
   ```
2. Go to [GitHub](https://github.com), click **New Repository**, name it `my-budget-dashboard`, and keep it Public (for free GitHub Pages hosting).
3. Link your local project to GitHub and push:
   ```bash
   git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/my-budget-dashboard.git
   git branch -M main
   git push -u origin main
   ```

---

### Step 3: Enable GitHub Pages (Instant Free Mobile Access)
1. On your GitHub repository page, click **Settings** (gear icon in the top tabs).
2. On the left sidebar, click **Pages**.
3. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
4. Within 1–2 minutes, GitHub will give you a live HTTPS web link:
   ```
   https://<YOUR_GITHUB_USERNAME>.github.io/my-budget-dashboard/
   ```

---

### Step 4: Open and Save to Your Phone's Home Screen
1. Open the GitHub Pages link on your mobile phone browser (Safari on iPhone or Chrome on Android).
2. Connect your Google Sheet following `google_sheets_setup_guide.md`.
3. Add to Home Screen:
   - **iPhone (Safari)**: Tap the **Share** button (box with arrow) -> **Add to Home Screen**.
   - **Android (Chrome)**: Tap the **Three Dots** menu -> **Add to Home screen** (or **Install app**).
4. You now have a standalone budget app icon on your phone that connects directly to your Google Sheet!
