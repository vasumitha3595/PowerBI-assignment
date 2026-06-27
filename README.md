# 📊 Power BI Assignment 1 – Data Transformation & Data Modeling

## 📌 Project Overview

This project demonstrates the complete process of **data transformation, data cleaning, aggregation, and data modeling** using **Microsoft Power BI**. The assignment uses an E-commerce sales dataset consisting of multiple CSV files and focuses on preparing data for analysis using Power Query and establishing relationships between tables.

---

## 🎯 Objectives

* Import multiple datasets into Power BI.
* Perform data cleaning and transformation using Power Query.
* Create custom and conditional columns.
* Merge related datasets.
* Handle duplicate and missing values.
* Perform sorting, filtering, grouping, and aggregation.
* Build an optimized data model using relationships.
* Create report visuals for business insights.

---

## 📂 Dataset

The project uses the following datasets:

* **List of Orders.csv**
* **Order Details.csv**
* **Sales Target.csv**

---

## ⚙️ Tasks Performed

### 1. Data Import

* Imported all three CSV datasets into Power BI.
* Opened datasets in Power Query Editor for transformation.

### 2. Data Transformation

* Limited **List of Orders** to the first **500 rows**.
* Converted **Order Date** to **Date** data type.
* Changed **Amount** and **Target** columns to **Fixed Decimal Number**.

### 3. Data Cleaning

* Converted **Customer Name** to Proper Case.
* Created a new **Location** column by merging **City** and **State**.
* Removed duplicate records.
* Verified and handled missing values where applicable.

### 4. Custom & Conditional Columns

Created:

* **Profit Margin**

  * Formula:

    ```
    Profit / Amount
    ```

* **Profit Status**

  * Profit > 0 → Profit
  * Profit = 0 → Break-Even
  * Profit < 0 → Loss

### 5. Merge Queries

Merged:

* **List of Orders**
* **Order Details**

using **Order ID** to create a new table named **Orders Data**.

### 6. Sorting & Filtering

* Sorted records by **Order Date** (Descending).
* Filtered records for **Tamil Nadu**.

### 7. Grouping & Aggregation

Performed aggregations including:

* Count of Order ID
* Average Profit by Category
* Total Amount by Sub-Category
* Total Target by Month

### 8. Data Modeling

Created relationships between:

* **List of Orders** ↔ **Order Details** (Order ID)
* **Order Details** ↔ **Sales Target** (Category)

All relationships were configured as active in Model View.

---

## 📈 Report Visuals

The final report includes:

* Order Count KPI
* Total Sales by Sub-Category
* Average Profit by Category
* Data Model View

---

## 🛠 Tools Used

* Microsoft Power BI
* Power Query Editor
* Data Modeling
* DAX (Basic)
* CSV Dataset

---

## 📁 Project Structure

```
PowerBI-Assignment-1/
│
├── PowerBI Assignment 1.pbix
├── README.md
├── Assignment_Report.pdf
├── Screenshots/
└── Dataset/
```

---

## 📚 Skills Demonstrated

* Data Import
* Data Cleaning
* Data Transformation
* Power Query
* Data Modeling
* Table Relationships
* Aggregation
* Business Intelligence
* Report Visualization

---

## ✅ Outcome

Successfully transformed raw E-commerce data into a clean and structured Power BI data model by applying Power Query transformations, data quality techniques, aggregations, and relationship modeling. The final report provides meaningful business insights through interactive visualizations.

---

## 👨‍💻 Author

**Name:** Vasumitha
**Course:** Data Analytics – Module 2
**Tool:** Microsoft Power BI
