#  Sales & Performance Interactive Analytics Dashboard (Excel)

An interactive, multi-page business intelligence dashboard built entirely in **Microsoft Excel**. This project delivers comprehensive visibility into sales revenue, regional distribution, product category profitability, and sales representative performance through clean data modeling, advanced Pivot Tables, and interactive slicers.

---

##  Project Overview & Structure

The dashboard is structured into four specialized analytical views:

1. ** Overview Dashboard:** High-level executive summary tracking Total Sales, Total Orders, Average Order Value (AOV), monthly trends, and deep-dive analysis on Discount impact vs. Profit Margins.
2. ** Sales Representative Dashboard:** Individual performance metrics, revenue contribution, top product category per rep, customer retention (New vs. Returning), and payment method breakdowns.
3. ** Category Dashboard:** Profitability, total volume, channel distribution, and monthly seasonality across product categories (*Furniture, Clothing, Electronics, Food*).
4. ** Region Dashboard:** Regional breakdown (*North, East, West, South*), online vs. retail channel performance, and monthly regional profit trends.

---

## 🛠️ Data Pipeline & Workflow

### 1. Data Cleaning & Preprocessing
- **Data Validation & Type Casting:** Standardized date formats, currency columns, and categorical classifications.
- **Handling Inconsistencies & Duplicates:** Cleaned missing values, removed duplicate transactions, and standardized naming conventions across regions and sales reps.
- **Feature Engineering & Calculated Fields:**
  - `Revenue` & `Profit Margin` calculations after applied discounts.
  - Extraction of temporal features (`Month`, `Quarter`, `Year`).
  - Customer segmentation flags (`New` vs. `Returning` customers).

### 2. Analytical Modeling & Pivot Tables
- Built dedicated backend Pivot Tables to dynamically aggregate:
  - Multi-level metrics (Sales Rep × Category × Payment Method).
  - Discount threshold analysis and price elasticity trends.
  - Channel sales distribution (Online vs. Retail).
- Utilized Excel Formulas (`XLOOKUP`, `INDEX/MATCH`, `SUMIFS`, `GETPIVOTDATA`) to power dynamic KPI summary cards.

### 3. Dashboard Design & Interactivity
- **Dynamic Slicers:** Unified timeline and discount filters connected across multiple Pivot Tables and visual layers.
- **Visual Palette & UX:** Custom, cohesive theme with consistent typography, branded header navigation, and intuitive reset actions.
- **Chart Optimization:** Stacked bar charts, trend lines, donut/pie breakdowns, and combo charts formatted for clear readability without visual clutter.

---

## 💡 Key Business Insights

- **Discount Sensitivity:** Discounts above 1% exhibit diminishing profit margins, highlighting the need to optimize promotional strategies.
- **Top Performers:** Sales representative performance varies heavily by category expertise (e.g., David dominating Revenue & Electronics, while Eve leads in Average Order Value).
- **Product Profitability:** Furniture and Clothing consistently yield the highest profit margins despite seasonality fluctuations.
- **Regional Balance:** The North region generates the highest overall profit and order volume, with a balanced distribution between Online and Retail channels.

---
