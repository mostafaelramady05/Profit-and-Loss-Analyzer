# 📊 **Financial Dashboard with What-If Analysis**

## 📌 **Overview**
This Power BI dashboard provides a dynamic analysis of a company’s financial performance, focusing on Profit and Loss (P&L), revenue, cost changes, and operating income. The project incorporates **What-If analysis** to simulate various financial scenarios, enabling informed decision-making.

## 🔍 **Key Features**
- **Dynamic P&L Visualization** with customizable account ordering
- **Advanced DAX Measures** for calculating revenue, costs, and operating income
- **What-If Analysis** for scenario-based financial planning
- **Interactive Filters** for deep dives into financial data
- **Vertical & Horizontal Analysis** for trend insights and performance comparisons

---

## 📊 **Page 1: Financial Overview**
### **Key Insights:**
- **Total Revenue:** 1,200,000 EGP
- **Operating Income:** 500,000 EGP
- **Cost of Goods Sold (COGS):** 600,000 EGP
- **Expenses:** 100,000 EGP

### **Visualizations:**
- **Revenue & COGS Trends** (Line Chart)
  - Shows revenue and COGS from January to March 2025.
  - **DAX Title:** `"📈 Revenue & COGS Trends (Jan - Mar 2025)"`
 
- **Operating Income Analysis** (Bar Chart)
  - Displays the operating income calculated from revenue and COGS.
  - **DAX Measure:** `OperatingIncome`

- **Expense Breakdown** (Pie Chart)
  - Shows the distribution of various expenses.
  - **DAX Title:** `"📊 Expense Distribution"`

---

## 📊 **Page 2: What-If Scenario Analysis**
### **Key Insights:**
- **What-If Revenue Change:** -5% to +10%
- **What-If Expense Adjustment:** -10% to +5%
- **Cost Impact Simulation:** Scenario modeling for various COGS percentages

### **Visualizations:**
- **Revenue Sensitivity Analysis** (Line Chart)
  - Simulates the effect of different revenue growth rates on operating income.
  - **DAX Measure:** `RevenueScenarioImpact`

- **Cost & Expense Scenario** (Clustered Bar Chart)
  - Displays how varying expense adjustments and COGS impact profitability.
  - **DAX Measure:** `CostScenarioAnalysis`

- **Scenario Comparison Table** (Table)
  - Compares multiple financial scenarios with different assumptions for key metrics.
  - **DAX Measure:** `ScenarioComparison`

---

## 📊 **Page 3: Vertical & Horizontal Analysis**
### **Key Insights:**
- **Vertical Analysis by Account Type:** Measures each account as a percentage of total revenue
- **Horizontal Analysis:** Tracks financial performance trends over time.

### **Visualizations:**
- **Vertical Analysis Chart** (Stacked Column Chart)
  - Shows each account’s percentage of revenue for the selected period.
  - **DAX Measure:** `VerticalAnalysisPercent`

- **Revenue & Profit Trend** (Line Chart)
  - Compares revenue and profit growth over time.
  - **DAX Measure:** `RevenueProfitTrend`

- **Financial Comparison Table** (Matrix)
  - Provides a detailed year-over-year financial comparison.
  - **DAX Title:** `"📅 Financial Comparison (Year-over-Year)"`

---

## 📌 **Tooltip Pages**
### **Advanced Tooltips for Contextual Insights**
- **Scenario Impact:** Shows key metrics for selected financial scenarios.
- **P&L Insights:** Displays detailed revenue and cost breakdowns for selected periods.
- **Profitability Trends:** Highlights changes in operating income over time.

---

## 🎨 **Dashboard Design & Formatting**
- **Color Palette:**
  - `#2F3A75` (Primary)
  - `#1E72C3` (Accent)
  - `#5A94D9` (Secondary)
  - `#4071D2` (Highlights)
  - `#F1F1F1` (Background)
- **Conditional Formatting Applied:**
  - Revenue Growth Rate
  - Scenario Sensitivity
  - Profitability Comparison

---

## 📂 **Repository Structure**
