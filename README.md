# 📊 **Financial Dashboard for Profit and Loss Analyzer**

## 📌 **Overview**
This Power BI dashboard provides a dynamic analysis of a company’s financial performance, focusing on Profit and Loss, revenue, cost changes, and operating income. The project incorporates **What-If analysis** to simulate various financial scenarios, enabling informed decision-making.

## 🔍 **Key Features**
- **Interactive P&L Visualization** with flexible account sorting
- **Advanced DAX Measurements** for calculating revenue, costs, and operating income
- **What-If Analysis** for scenario-based financial planning
- **Interactive Filters** for deep dives into financial data
- **Vertical & Horizontal Analysis** for trend insights and performance comparisons

---
## 📊 **Page 1: Revenue & Margin Analysis**
### **Key Insights:**
- **Revenue Trends:** Understand how revenue has evolved.
- **Gross Margin (GM):** Analyze gross margin and GM percentage to assess profitability.
- **Monthly Breakdown:** View detailed month-by-month comparisons of revenue and margin.

- **Gross Margin (%) by Month** (Column Chart)
  - Shows the GM percentage for each month.
  - **DAX Measure:** `GrossMarginMonthByMonth`

- **Supplier Performance** (Table)
  - Displays supplier-wise revenue, gross margin, and GM%.
  - **DAX Measure:** `SupplierRevenueGM`

---

## 📊 **Page 2: Income Statement**
### **Key Insights:**
- **Revenue, Costs, & Expenses:** Track key income statement metrics.
- **Operating Income:** Monitor the net impact of revenue, cost, and expenses on income.
- **Income % Analysis:** See how income compares to overall revenue.

### **Visualizations:**
- **Revenue & Cost Trends** (Bar Chart)
  - Displays revenue and cost trends over time.
  - **DAX Measure:** `RevenueCostTrends`

- **Income Breakdown** (Clustered Column Chart)
  - Compares revenue, cost, and income for detailed analysis.
  - **DAX Measure:** `IncomeBreakdown`

- **Waterfall Chart (Income Impact)** (Waterfall Chart)
  - This shows how income changes month by month based on revenue, costs, and expenses.
  - **DAX Title:** `"💸 Monthly Income Breakdown"`

- **P&L, VA, HA Comparison** (Table)
  - Compares Profit & Loss, Vertical Analysis, and Horizontal Analysis for better performance tracking.
  - **DAX Measure:** `PnlVAHAComparison`

---

## 📊 **Page 3: P&L Simulator**
### **Key Insights:**
- **Scenario-Based Analysis:** Simulate the impact of changes in revenue, costs, and expenses on your bottom line.

