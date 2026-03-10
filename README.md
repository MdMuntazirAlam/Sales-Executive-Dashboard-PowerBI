# Sales-Executive-Dashboard-PowerBI
## An interactive Power BI dashboard analyzing global sales performance and regional trends

<img width="620" height="354" alt="image" src="https://github.com/user-attachments/assets/dccc4044-7fde-4eac-96f5-081b6f46165e" />


## 📊 Project Overview

This project features a comprehensive Executive Sales Report built in Power BI Desktop. It transforms the classic AdventureWorks dataset into a strategic tool for monitoring revenue, order volume, and regional market share.

The dashboard provides a high-level view of $109.81M in Total Sales and identifies key growth drivers across various business types and product categories.

## 🚀 Key Insights from the Report

Top Revenue Driver: The Bikes category is the powerhouse of the business, contributing $66.3M to total sales.

Market Dominance: The United States is the leading region ($63M), followed by Canada ($16M) and Australia ($11M).

Seasonality: Sales peaked significantly in November at $13.5M, showing strong year-end performance.

Business Channels: High-volume sales are driven primarily through Warehouse and Value Added Resellers, while Specialty Bike Shops show a smaller, more boutique market share.

## 🛠️ Technical Architecture

I have implemented a Star Schema data model to ensure high performance and accurate filtering across all visuals.

**Data Model Components:**

Fact Table: Sales (containing keys, quantities, and sales amounts).

Dimension Tables: Product, Customer, Reseller, Sales Territory, Date, and Sales Order.

Logic: Managed 1:N (One-to-Many) relationships to allow seamless slicing by Year, Month, Country, and Category.

**Calculations (DAX):**

**The report utilizes several DAX measures, including:**

Total Sales: Aggregated revenue across all transactions.

Total Orders: Count of unique sales orders (121K total).

Sales Amount by Due Date: A time-intelligence measure to track revenue against fulfillment deadlines.

## 📂 Repository Contents

**Sales Report.pbix:** The interactive Power BI project file (requires Power BI Desktop to open).

**AdventureWorks Sales.xlsx:** The source data containing Sales, Products, Customers, and Territory details.

## 🔧 How to View This Project

**Download & Install:** Ensure you have the latest version of Power BI Desktop.

**Download the Files:** Clone this repository or download the .pbix and .xlsx files.

**Open:** Launch the Sales Report.pbix file.

**Reconnect Data (If prompted):**

Go to Transform Data > Data Source Settings.

Change the Source path to point to the AdventureWorks Sales.xlsx file on your local machine.

## 💡 Skills Demonstrated

**Data Cleaning:** Using Power Query to handle nulls and format data types.

**Data Modeling:** Designing a Star Schema for optimal report performance.

**Data Visualization:** Creating intuitive layouts, KPI cards, and trend lines.

**Business Intelligence:** Converting raw data into strategic business recommendations.

## Connect with Me

Feel free to connect if you have feedback or questions!

E-mail : mdmuntaziralam15@gmail.com

LinkedIn : www.linkedin.com/in/md-muntazir-alam-74a9433a0

