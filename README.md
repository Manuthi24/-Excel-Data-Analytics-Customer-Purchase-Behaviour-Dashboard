## 📌 Project Overview

![Excel](https://img.shields.io/badge/Excel-Data%20Analytics-blue)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive%20Insights-green)
![PivotTables](https://img.shields.io/badge/PivotTables-%26%20Charts-yellow)
![PowerQuery](https://img.shields.io/badge/PowerQuery-Data%20Prep-orange)
![Customer Analytics](https://img.shields.io/badge/Customer-Analytics-red)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black)
![Portfolio Project](https://img.shields.io/badge/Type-Portfolio%20Project-important)

This project demonstrates an **end-to-end data analytics workflow** using **Microsoft Excel**. The objective was to transform a raw dataset of **1,000 customers** into a professional, interactive dashboard that identifies the demographic factors influencing bike purchases.  

By cleaning the data and building dynamic visualisations, the project provides clear insights into how **income, age, and commute distance** impact consumer behaviour.

---

## 📊 Key Features & Workflow

### 1. Data Cleaning and Preparation
Before analysis, the raw data underwent a rigorous cleaning process to ensure **accuracy and readability**:
- **Duplicate Removal:** Removed duplicate entries to maintain data integrity.
- **Data Standardisation:** Expanded abbreviations in the "Marital Status" and "Gender" columns (e.g., "M" → "Married", "S" → "Single", "F" → "Female") for user-friendly representation.
- **Currency Formatting:** Formatted income data as currency and removed unnecessary decimals for cleaner visuals.

### 2. Feature Engineering (Age Brackets)
To improve clarity, individual ages (25–89) were grouped into categories using a nested IF statement:
- **Adolescent:** Under 31  
- **Middle Age:** 31–54  
- **Old:** 55 and above  

### 3. Pivot Tables & Data Analysis
Pivot Tables were created to summarize the data and drive the dashboard visualisations:
- **Income Analysis:** Compared average income of bike buyers vs non-buyers by gender.  
- **Commute Analysis:** Counted purchases based on distance customers travel to work.  
- **Age Demographics:** Analysed purchase trends across age brackets.

### 4. Interactive Dashboard Development
The dashboard was designed as a **dynamic tool for stakeholders**:
- **Dynamic Visualisations:** Clustered column charts for income, line charts for age trends, and distance-based graphs.  
- **Interactive Slicers:** Filters for "Marital Status", "Region", and "Education" linked to all charts via Report Connections.  
- **UI Optimisation:** Clean, professional layout with removed gridlines, bold header, and aligned charts.

---

## 🚀 Key Insights
- **Income Correlation:** Customers who purchased bikes generally had a **higher average income**.  
- **Age Trends:** The **Middle Age** bracket (31–54) is the most active demographic for bike purchases.  
- **Commute Impact:** Commute distance significantly influences purchase likelihood, with specific fluctuations across ranges.

---

## 🛠️ Tools Used
- **Microsoft Excel**  
  - Data Cleaning & Formatting  
  - Pivot Tables & Nested IF Formulas  
  - Data Visualisation & Charts  
  - Interactive Dashboard Design & UI Optimisation

---

## 📁 Project Files
```text
├── Bike_Sales_Project.xlsx  # Main Excel file with data, pivot tables, and dashboard
└── README.md                # Project documentation
