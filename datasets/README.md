# Datasets

This folder contains the source datasets used across the Power BI projects in this portfolio.

The purpose of including these datasets is to provide **full transparency**, enable **reproducibility**, and clearly document the data foundations behind each analytical solution.

All transformations, modeling, and calculations are performed inside Power BI using Power Query and DAX.  
The files stored here represent the **raw or lightly structured inputs**, not the final analytical models.

---

## ☕ Café Sales Dataset
**File:** `Arabic_Coffe_Sales_Dataset.xlsx`

A transactional sales dataset used for the introductory café sales analysis.

### Dataset Scope
- Sales transactions by branch
- Product categories and individual items
- Payment methods
- Transaction dates
- Quantities, costs, revenues, and profits

### Analytical Usage
- KPI calculation (Sales, Profit, Cost, Quantity)
- Branch and product performance comparison
- Time-based sales trends
- Management-level reporting

### Used In
- **01_cafe_sales_dashboard**

---

## 🛒 E-Commerce Sales Dataset
**File:** `Dataset_E-Commerce.xlsx`

A structured e-commerce dataset designed for analytical modeling and advanced reporting.

### Dataset Scope
- Sales fact table with transactional records
- Dimension tables:
  - Customers
  - Products
  - Locations
  - Segments
  - Shipping modes
  - Calendar
- Suitable for normalization and star schema modeling

### Analytical Usage
- Data modeling (Fact & Dimensions)
- Time intelligence (YOY, MOM, QOQ)
- Customer and product performance analysis
- Retention and profitability analysis
- Advanced interactive dashboards

### Used In
- **02_ecommerce_sales_modeling**
- **03_ecommerce_advanced_dashboard**

---

## 📌 Notes

- Datasets are included for **portfolio and demonstration purposes only**
- All data cleaning, normalization, and enrichment are performed within Power BI
- Original datasets are preserved here to maintain:
  - Traceability
  - Reproducibility
  - Analytical clarity
- No manual edits are applied directly to these files after ingestion

---

## 🔍 How to Use

To explore the projects:
1. Navigate to the `projects` folder
2. Open any project folder
3. Review the project-specific README for context
4. Open the corresponding `.pbix` file in Power BI Desktop

---

This datasets structure is intentionally kept clean and minimal to reflect **professional analytical workflows** and **industry best practices**.
