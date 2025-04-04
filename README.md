# 🧾 Financial Operations Audit Dashboard

## 📌 Project Summary
This project simulates a real-world internal audit workflow for a mid-sized biotech company. It analyzes purchase orders, invoices, vendor profiles, and general ledger entries to identify financial inconsistencies, payment delays, and potential audit risks.

## 🎯 Objectives
- Detect unmatched invoices and purchase orders
- Identify high-risk vendors with significant transaction volumes
- Evaluate department-level spending trends
- Analyze payment cycle efficiency and flag anomalies
- Present audit findings with clear visualizations and insights

## 🛠️ Tech Stack
- **Python**: Data analysis (pandas), visualization (matplotlib, seaborn)
- **Excel**: Simulated datasets
- **Jupyter Notebook**: Step-by-step data exploration
- **(Optional)**: Power BI or Tableau for dashboard creation

## 🗂️ Data Sources
- `PurchaseOrders`: Simulated PO records by department
- `Invoices`: Vendor billing details and payment status
- `LedgerEntries`: Accounting entries for financial activity
- `Vendors`: Supplier information and risk level

## 📊 Key Analyses
- 🔍 Unmatched Invoices: Invoices that have no linked purchase orders
- 🚨 High-Risk Vendors: Suppliers labeled 'High' risk with high transaction volume
- 🏢 Department Spend: Total spend across functional units
- ⏱️ Payment Cycle: Days between PO creation and invoice issue
- ❗ Anomalies: Outliers in payment behavior based on statistical thresholds

## 📈 Sample Visuals
- Department spending bar chart
- Payment cycle distribution histogram
- Flagged outlier transactions table

## 📥 How to Use
1. Clone the repo
2. Open `notebooks/audit_analysis_final.ipynb` in Jupyter
3. Run cells in order to explore the data
4. Modify or extend with your own audit logic

---

📣 This project is a great example of how Data Analysts can add value to Finance teams by ensuring compliance, detecting irregularities, and delivering clear, data-driven insights.
