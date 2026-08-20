# 📊 HR & Business Performance Dashboard 
 
> **An interactive Power BI dashboard designed to transform HR and business data into clear, actionable insights.** 
 
--- 
 
## 🚀 Project Overview 
 
This project focuses on analyzing employee, compensation, business, and performance-related data using **Microsoft Power BI**. 
 
I created an interactive one-page dashboard with **DAX measures, KPI cards, charts, custom icons, and slicers** to make the analysis easy to explore. 
 
### 🎯 Main Objective 
 
The goal was to turn raw data into a **clear visual story** and answer important business questions related to: 
 
- 💰 Salary & Bonus 
- 🎓 Education 
- 👥 Gender & Dependents 
- 🏷️ Unit Price 
- 📅 Monthly Volume 
- 👤 Age & Salary 
- 📊 Business Types 
 
--- 
 
## ⭐ Key KPIs 
 
| KPI | Purpose | 
|---|---| 
| 💰 **Total Bonus** | Overall bonus value | 
| 💼 **Avg Salary** | Average employee salary | 
| 👥 **Total Records** | Total number of records | 
| 🏷️ **Avg Unit Price** | Average unit price | 
| 👤 **Avg Age** | Average age | 
| 💵 **Avg Bonus** | Average bonus | 
 
--- 
 
## 📈 Dashboard Analysis 
 
The dashboard contains: 
 
- **Gender Distribution** 
- **Average Salary by Education** 
- **Average Unit Price by Type** 
- **Gender by Dependents** 
- **Total Volume by Month** 
- **Average Bonus by Education** 
- **Age vs Salary** 
- **Average Age by Type** 
 
--- 
 
## 🎛️ Interactive Dashboard 
 
Users can filter the dashboard using: 
 
**Education | Type | Months | Gender** 
 
The **Months** slicer uses a **Between** filter covering **72 month periods**, allowing users to analyze specific time ranges. 
 
---

## 🧮 DAX Measures

I created DAX measures to calculate the key metrics used throughout the dashboard.

### Average Salary

```DAX
Average Salary = AVERAGE(HRData[Salary])
```

### Average Bonus

```DAX
Average Bonus = AVERAGE(HRData[Bonus])
```

### Average Age

```DAX
Average Age = AVERAGE(HRData[Age])
```

### Average Unit Price

```DAX
Average Unit Price = AVERAGE(HRData[Unit_Price])
```

### Total Records

```DAX
Total Records = COUNTROWS(HRData)
```

### Total Bonus

```DAX
Total Bonus = SUM(HRData[Bonus])
```

These DAX measures were used to create dynamic KPI cards and support the dashboard's interactive analysis.

---

## 🔍 Business Questions Answered

This dashboard helps answer the following business questions:

### 1. 💼 Salary & Education
How does average salary vary across different education levels?

### 2. 💰 Bonus & Education
How does average bonus differ across education levels?

### 3. 👥 Gender Distribution
How is the workforce distributed by gender?

### 4. 👨‍👩‍👧 Gender & Dependents
How does gender distribution vary across different numbers of dependents?

### 5. 🏷️ Unit Price Analysis
How does average unit price differ across different types?

### 6. 📅 Monthly Volume
How does total volume change across the 72-month period?

### 7. 📈 Age & Salary
Is there a relationship between age and salary?

### 8. 👤 Type & Age
How does average age vary across different types?

---

## 🛠️ Tools & Skills

**Microsoft Power BI** • **DAX** • **Data Analysis** • **Data Visualization** • **Dashboard Design** • **KPI Development** • **Interactive Slicers**

---

## 🎨 Dashboard Design

The dashboard follows a consistent **purple-themed professional design** with:

- 💜 Purple KPI cards
- 📊 Consistent purple chart colors
- 🎯 Custom KPI icons
- 🎛️ Interactive slicers
- 📐 Clean visual hierarchy
- 📄 One-page dashboard layout

---

## 📷 Dashboard Preview

![HR & Business Performance Dashboard](./https://github.com/raghavverma200420-star/HR-Business-Performance-Dashboard/blob/c68a72aea382b3c9ed3a68f40ed9d2a995010ecd/Dashboard_Screenshort.png)

---

## 📂 Project Files

- `README.md` — Project documentation
- `HR_Business_Performance_Dashboard.pbix` — Power BI dashboard file
- `dashboard_screenshot.png` — Dashboard preview

---

## 💡 Key Learnings

Through this project, I improved my ability to:

- Build interactive Power BI dashboards
- Create and use DAX measures
- Design KPI cards
- Use slicers and filters
- Choose appropriate visualizations
- Analyze relationships and trends
- Create clear data stories
- Design professional dashboard layouts
- Present analytical insights effectively

---

## 🚀 Future Improvements

- Add more advanced DAX calculations
- Add drill-through analysis
- Add additional time-based KPIs
- Add automated data refresh
- Add more advanced business metrics

---

## 👤 Author

### Raghav Verma

**Aspiring Data Analyst | Business Analyst**

**Skills:** Power BI • DAX • Excel • Data Analytics

---

⭐ **If you find this project useful, feel free to explore the repository and share your feedback.**
