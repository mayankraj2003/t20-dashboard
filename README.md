# 🏏 T20 Cricket Dashboard (Power BI)

## 📊 Project Overview

This project is an interactive **T20 Cricket Dashboard** built using Power BI to analyze player and team performance.

The dashboard delivers insights into batting, bowling, and overall match statistics with a clean and user-friendly interface.

---

## 🎯 Objectives

* Analyze player performance (Batsmen & Bowlers)
* Compare team statistics
* Identify top performers
* Visualize key cricket metrics

---

## 🔧 Tools & Technologies Used

* 📊 Power BI
* 📁 Excel / CSV
* 📈 Data Visualization Techniques

---

## 🧠 Key Concepts Used

### 📊 Power BI Concepts

* Data Modeling (table relationships)
* DAX (Data Analysis Expressions)
* Calculated Columns & Measures
* Data Cleaning using Power Query
* Interactive Dashboard Design
* Filters & Slicers
* Drill-through Navigation

---

### ⚡ Important DAX Measures

```DAX
Total Runs = SUM(dataset[runs])

Total Wickets = SUM(dataset[wicket])

Strike Rate = 
DIVIDE(SUM(dataset[runs]), SUM(dataset[balls])) * 100

Economy Rate = 
DIVIDE(SUM(dataset[runs_conceded]), SUM(dataset[overs]))

Total Matches = DISTINCTCOUNT(dataset[match_id])
```

---

### 📑 Excel Concepts Applied

* Data Cleaning (duplicates, blanks)
* Sorting & Filtering
* Pivot Tables
* Conditional Formatting
* VLOOKUP / XLOOKUP
* Data Validation
* Core Functions (SUM, COUNT, AVERAGE)

---

### 🔄 Data Preprocessing

* Handled missing values
* Standardized column names
* Converted data types
* Ensured data consistency

---

## 📌 Key Features

* 🏏 Batsman performance (Runs, Strike Rate)
* 🎯 Bowler analysis (Wickets, Economy)
* 📊 Interactive filters (Team selection)
* 📈 Dynamic visuals & charts
* 🏆 Key KPIs (Centuries, Sixes, Fours)

---

## 📷 Dashboard Preview

![Dashboard](dashboard.png)

---

## 📂 Project Structure

```
T20-Dashboard/
│── T20_Dashboard.pbix
│── dataset.csv
│── dashboard.png
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Explore interactive dashboard

---

## 💡 Key Insights

* Top-performing batsmen
* Best strike rates
* Leading wicket-takers
* Team-wise comparisons

---

## 📈 Future Enhancements

* Add advanced KPIs using CALCULATE & RANKX
* Player comparison dashboard page
* Improved UI/UX design
* Real-time data integration

---

## 👤 Author

**Mayank Raj**

🔗 LinkedIn: https://www.linkedin.com/in/mayank-raj-790825281?utm_source=share_via&utm_content=profile&utm_medium=member_android

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub!

---
