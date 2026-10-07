# BudgetIQ – Intelligent Financial Ledger & Subscription Manager

A responsive, modern single-page financial web application built with vanilla HTML5, CSS3, and modern JavaScript (ES6+), designed to competition specifications.

[🚀 Live Demo](https://budgetiq-app.netlify.app)

---

## 🌟 Key Features

### 1. 🔐 Authentication & Session Persistence
* **Sign In & Account Registration:** Complete user registration and login system.
* **LocalStorage Persistence:** User credentials, session tokens, financial ledgers, and recurring bill records are persisted locally across browser refreshes and reboots.
* **Per-User Data Isolation:** Multi-account support where ledger and subscriptions are scoped to each specific user account.
* **Instant Demo Mode:** A single-click tester button signed in as *Alex Morgan* pre-loaded with realistic financial data and upcoming bill alerts for evaluation.

### 2. 📊 Module 1 – Expense & Income Ledger Engine
* **Summary Cards:**
  * **Net Cashflow:** Dynamic real-time calculation with surplus/deficit status indicators and savings rate percentage.
  * **Total Income:** Gross earned inflows with record count.
  * **Total Outflows:** Aggregated expenditures with percentage of income consumed.
  * **Projected Recurring:** Normalized monthly subscription burden.
* **Transaction Entry Form:**
  * **Fields:** Title, Amount ($), Date, Category (**Food, Rent, Utilities, Transport, Salary**, Entertainment, Health, Other), and Flow Type (**Income / Expense**).
  * Segmented color-coded flow switcher with default date assignment.
* **Browsable History Table:**
  * **Real-time Live Search:** Instant search filtering across title, category, and date.
  * **Multi-Criteria Filtering:** Filter by category (Food, Rent, Utilities, etc.) and flow type (All, Income, Expense).
  * **Sorting:** Sort by newest date, oldest date, highest dollar amount, or lowest dollar amount.
  * **Record Deletion:** Quick deletion of individual records with real-time recalculation of all financial metrics.
  * **CSV Data Export:** One-click export of ledger records to CSV file.

### 3. 💳 Module 3 – Subscription & Recurring Bill Manager
* **Recurring Bill Logging:** Track recurring commitments (Netflix, Internet, Rent, Spotify, Gym, etc.) with frequency (**Monthly, Yearly, Weekly, Quarterly**) and next billing dates.
* **7-Day Proximity Alert Engine:**
  * High-visibility banner highlighting all bills due within the next 7 days (or overdue).
  * Visual status tags: `DUE TODAY!`, `Due in 1 day`, `Due in X days`, or `OVERDUE`.
* **Mark Paid & Log to Ledger:** One-click action automatically creates a ledger expense record and increments the bill to its next billing cycle.
* **Projected Monthly Subscription Metric:** Intelligently converts all billing cadences into a normalized monthly spend figure ($/mo).

### 4. 🧠 AI Financial Assistant Panel (Neural Advisory Engine)
* **Algorithmic Ledger Analysis:** Button to analyze live cash flow, category distributions, and recurring commitments to generate **3 tailored natural-language recommendations**:
  1. **Cash Flow & Savings Velocity:** Analyzes burn rate, deficit warnings, or progress toward the 50/30/20 benchmark (20% savings rule) with specific dollar targets.
  2. **Category Outflow Optimization:** Detects the heaviest spending cluster (e.g. Food or Rent) and projects exact monthly and annual savings from a 15% reduction.
  3. **Subscription Overhead Audit:** Evaluates recurring subscriptions against net income and recommends audits if recurring load exceeds healthy boundaries.
* **Interactive AI Inquiries:** Quick interactive prompts ("Can I afford a $150 treat?", "How do I trim subscriptions?", "Evaluate my 50/30/20 balance") with tailored contextual modal responses.

### 5. 🎨 Design System (Warm Japandi & Porcelain Doll Aesthetic)
* **Warm Beige Background:** Natural ceramic washi backdrop (`#F7F3ED`) with subtle ambient sunlight and lavender glow.
* **Pastel Porcelain Card Containers:** Alternating soft light lavender (`#F2EEFC`) and pastel sky blue (`#EBF3FA`) glazed surfaces.
* **Delicate Lavender Accents:** Soft lavender highlights (`#8E7CC3`, `#9D8CD7`, `#6C59A4`) with gentle gradient buttons, sparkle badges, and focus rings.
* **Elegant Serif Typography:** Headings and titles set in Google Fonts *Playfair Display*, paired with *Plus Jakarta Sans* for clean body labels and *JetBrains Mono* for currency figures.
* **Porcelain Shapes:** Smooth, softly rounded porcelain corners (`border-radius: 22px`) across all cards, containers, dialogs, and tables.
* **Pill-Shaped Controls:** All buttons, inputs, tabs, chips, and toggles sculpted into smooth pills (`border-radius: 999px`).
* **Subtle Lavender Floral Corner Motifs:** Delicate vector botanical lavender sprigs integrated directly into the section corners with soft ambient opacity.

---

## 🚀 How to Run

1. Open `index.html` directly in any web browser (Chrome, Edge, Firefox, Safari).
2. Alternatively, serve via any static HTTP server (e.g. Live Server in VS Code).
3. Click **"One-Click Instant Demo Experience"** on the login screen to immediately explore the pre-populated dashboard, or register a new custom account.