# SuperStore-Retail-Dashboard-
SuperStore retail data analysis using Excel
# 📊 Excel Dashboard Project

## 📌 Project Overview

This project is an **interactive Excel Dashboard** developed to transform raw data into meaningful business insights.

The project uses **Power Query** for data cleaning and transformation, **Power Pivot** for data modeling and DAX calculations, and Excel **Pivot Charts, Charts, Slicers, and Filters** to create an interactive dashboard.

The goal of this project is to demonstrate practical **Data Analysis and Business Intelligence skills using Microsoft Excel**.

---

## 🎯 Project Objective

The main objectives of this project are:

* Clean and transform raw data using **Power Query**
* Build a structured data model using **Power Pivot**
* Create calculated measures using **DAX**
* Analyze data using Pivot Tables and Pivot Charts
* Create interactive visualizations using Charts
* Add Slicers and Filters for dynamic analysis
* Identify important trends, patterns, and business insights
* Present the analysis through an easy-to-understand dashboard

---

## ❓ Business Questions

The dashboard was designed to answer important business questions such as:

1. What is the overall performance of the business?
2. Which products/categories are performing the best?
3. Which products/categories have lower performance?
4. How does performance change over time?
5. Which regions/customers contribute the most?
6. What are the major trends and patterns in the data?
7. How do different categories compare with each other?
8. What insights can help support better business decisions?

---

## 🔄 Project Workflow

The project follows a structured data analysis workflow:

```text
Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Power Pivot
   ↓
Data Model
   ↓
DAX Measures
   ↓
Pivot Tables
   ↓
Pivot Charts & Charts
   ↓
Slicers & Filters
   ↓
Interactive Dashboard
   ↓
Business Insights
```

---

## 🧹 Data Preparation – Power Query

**Power Query** was used to prepare the raw data before analysis.

### Tasks performed:

* Removed unnecessary columns
* Handled missing values
* Removed duplicate records
* Corrected data types
* Cleaned inconsistent values
* Transformed columns where required
* Prepared the dataset for data modeling

This helped create a cleaner and more reliable dataset for analysis.

---

## 🧩 Data Model – Power Pivot

**Power Pivot** was used to create the data model and manage relationships between tables.

### Data Modeling Activities:

* Imported cleaned data into the Data Model
* Created relationships between relevant tables
* Organized tables for analysis
* Created calculated measures
* Used the Data Model for Pivot Tables and Charts

### Simplified Data Model

```text
                ┌─────────────────┐
                │   Fact Table    │
                │                 │
                │ Sales / Orders  │
                └────────┬────────┘
                         │
             ┌───────────┼───────────┐
             │           │           │
             ▼           ▼           ▼
        ┌─────────┐ ┌─────────┐ ┌─────────┐
        │ Product │ │Customer │ │  Date   │
        │  Table  │ │  Table  │ │  Table  │
        └─────────┘ └─────────┘ └─────────┘
```

> The actual relationships depend on the structure of the dataset used in the project.

---

## 🧮 DAX Measures

DAX (**Data Analysis Expressions**) was used in Power Pivot to create measures for the dashboard.

Example measures include:

```DAX
Total Sales = SUM(Sales[SalesAmount])
```

```DAX
Total Orders = DISTINCTCOUNT(Sales[OrderID])
```

```DAX
Average Sales = AVERAGE(Sales[SalesAmount])
```

```DAX
Total Quantity = SUM(Sales[Quantity])
```

These measures were then used in Pivot Tables, Pivot Charts, and dashboard visuals.

---

## 📊 Dashboard

The final dashboard provides an interactive view of the analyzed data.

### Dashboard Components

* KPI Cards
* Pivot Charts
* Excel Charts
* Trend Analysis
* Category Analysis
* Performance Comparison
* Slicers
* Filters
* Interactive visualizations

Users can interact with the dashboard using **Slicers and Filters** to analyze different segments of the data.

---

## ✨ Dashboard Features

### 🔹 Interactive Filters

Filters allow users to focus on specific parts of the dataset.

### 🔹 Slicers

Slicers provide an easy way to dynamically filter dashboard visuals.

### 🔹 Pivot Charts

Pivot Charts were used to summarize and visualize data efficiently.

### 🔹 Charts

Different charts were used to represent:

* Trends
* Comparisons
* Category performance
* Distribution
* Overall performance

### 🔹 KPI Analysis

Important metrics are displayed at the top of the dashboard for quick understanding.

### 🔹 Dynamic Analysis

When users change the Slicers or Filters, the dashboard updates accordingly.

---

## 🖼️ Dashboard Screenshot

Add your dashboard screenshot below:

```markdown
![Excel Dashboard](images/dashboard.png)
```

Example repository structure for the screenshot:

```text
images/
└── dashboard.png
```

---

## 🔍 Key Findings

The analysis helped identify important business patterns, including:

* Top-performing products/categories
* Low-performing products/categories
* Changes in performance over time
* Major contributors to overall performance
* Differences between different segments
* Important trends and patterns in the dataset

> **Note:** Replace these points with the actual findings from your dashboard to make the project more specific and credible.

---

## 🛠️ Tools & Technologies

| Tool / Feature      | Purpose                              |
| ------------------- | ------------------------------------ |
| **Microsoft Excel** | Data analysis and dashboard creation |
| **Power Query**     | Data cleaning and transformation     |
| **Power Pivot**     | Data modeling                        |
| **DAX**             | Creating calculated measures         |
| **Pivot Tables**    | Data summarization                   |
| **Pivot Charts**    | Interactive data visualization       |
| **Charts**          | Data visualization                   |
| **Slicers**         | Interactive filtering                |
| **Filters**         | Data exploration                     |

---

## 📁 Repository Structure

```text
Excel-Dashboard/
│
├── 📊 Excel_Dashboard.xlsx
│
├── 🖼️ images/
│   └── dashboard.png
│
├── 📄 README.md
│
└── 📂 data/
    └── dataset.csv
```

### File Description

* `Excel_Dashboard.xlsx` → Main Excel dashboard workbook
* `dashboard.png` → Dashboard screenshot
* `dataset.csv` → Dataset used for analysis
* `README.md` → Project documentation

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Excel_Dashboard.xlsx` in Microsoft Excel.
3. Navigate to the **Dashboard** sheet.
4. Use the **Slicers and Filters** to explore the data.
5. Interact with the charts and KPIs.
6. Review the key insights generated from the analysis.

---

## 📚 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* Power Query
* Power Pivot
* Data Modeling
* DAX
* Pivot Tables
* Pivot Charts
* Data Visualization
* Interactive Dashboard Development
* Business Analysis
* Business Intelligence
* Insight Generation

---

## 👤 Author

**Omraj Jadhav**

### 📌 Data Analytics Portfolio

This project is part of my **Data Analytics portfolio**, demonstrating my ability to transform raw data into actionable insights using Microsoft Excel.

---
