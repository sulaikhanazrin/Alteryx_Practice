# 🧪 Alteryx Case Studies – Data Cleaning & Transformation Projects

Welcome to my Alteryx project repository! 🚀  
This repository contains two end-to-end Alteryx workflows created as part of data cleaning, transformation, and business analysis practice.  
Each case study demonstrates various Alteryx tools and best practices used for real-world data tasks.

---

## 📁 Case Study 1: Retail Sales Data Analysis

**Scenario:**  
A retail chain hired me to analyze their sales and product data coming from multiple sources.  
The task involved cleaning, transforming, and analyzing the data to provide insights for operations and marketing.

### 🔧 Tools & Techniques Used
- **Input, Browse, Auto Field**: Loaded all datasets and adjusted data types.
- **Filter, Formula, Select**: Filtered South region data, calculated `TotalSale`, and removed unnecessary columns.
- **Join, Join Multiple**: Merged Sales, Product, and Customer data using `ProductID` and `CustomerID`.
- **Sample, Unique, Sort**: Sampled data subsets and found unique `CustomerIDs`.
- **Find Replace**: Replaced category names with friendly descriptions.
- **Transform Tools**: Used `Cross Tab`, `Transpose`, `Summarize` for pivoting and aggregation.
- **Parse Tools**: Used `Regex`, `Text to Columns`, and `DateTime` parsing.
- **Record-Level Tools**: `Generate Rows`, `Record ID`, and `Append Fields`.
- **Documentation**: Tool containers and comments for workflow clarity.

### 📌 Output Highlights
- Top-selling product per region.
- Sales trend report by month and year.
- Customer ranking based on spend.

📄 **File**: `CaseStudy1_Workflow.yxmd`

---

## 📁 Case Study 2: HR & Payroll Data Transformation

**Scenario:**  
This case study uses a multi-sheet Excel file for employee, department, salary, and joining date data.  
The goal was to integrate, cleanse, and analyze data to generate HR insights.

### 🔧 Tools & Techniques Used
- **Union Tool**: Merged `Employee` and `EMP2` sheets (Auto-config by Name vs Position).
- **Join Tools**: Joined Employee with Department and Payslip with Joining_Date.
- **Find Replace**: Replaced department codes with names.
- **DateTime**: Standardized joining dates and extracted Year, Month, Day.
- **RegEx / Text to Columns**: Parsed email usernames and domain names.
- **Cross Tab / Transpose**: Salary trend per month by employee.
- **Summarize**: Calculated total, average, min, max salary by rank/department.
- **Formula Tool**: Created `Full_Name`, `Tenure`, and `Net_Salary` fields.
- **Filter Tool**: Extracted employees with salary > ₹50,000 or joined in 2011.
- **Select Records / Sample Tool**: Picked record ranges (e.g., last 3 employees, random samples).
- **Sort, Unique, Record ID**: Sorted by salary, assigned row IDs, found unique titles.

### 📌 Output Highlights
- Employee-wise salary and tenure view.
- HR dashboard-ready dataset with no missing values.
- Salary summary by department and rank.

📄 **File**: `CaseStudy3_Workflow.yxmd`

---

## ✅ How to Use
1. Open `.yxmd` files in Alteryx Designer.
2. Ensure sample data files are available (replace Input paths if needed).
3. Run workflows and explore the outputs using Browse tools.

---
