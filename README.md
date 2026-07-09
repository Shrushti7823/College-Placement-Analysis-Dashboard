# 🎓 College Placement Analysis Dashboard

An interactive **Power BI Dashboard** developed to analyze college placement data and provide meaningful insights into student placements, salary trends, company hiring patterns, branch performance, and skill-based analysis.

📊 This project transforms raw placement data into dynamic visualizations using **Power BI**, **Power Query**, and **DAX**, enabling users to make informed decisions through interactive reports.

---

## Project Overview

The **College Placement Analysis Dashboard** is designed to help placement coordinators, faculty members, and students analyze placement statistics efficiently.

The dashboard provides:

- Overall placement performance
- Branch-wise placement analysis
- Company-wise hiring insights
- Average salary analysis
- Student skill analysis
- Placement trends
- Interactive filtering and drill-down

---

## Features

- 📊 Interactive Power BI Dashboard
- 📈 Placement Percentage Analysis
- 👨‍🎓 Total Students & Placed Students KPI
- 💰 Average Salary Dashboard
- 🏢 Company-wise Hiring Analysis
- 🎯 Branch Performance Analysis
- 📚 Skill-wise Placement Insights
- 📍 Location-wise Placement Distribution
- 📅 Year-wise Placement Trends
- 🔍 Interactive Filters (Slicers)
- 📉 Scatter, Bar, Pie, Area, Gauge & Donut Charts

---

## 📊 Dashboard KPIs

- Total Students
- Placed Students
- Placement Percentage
- Average Salary
- Company-wise Placements
- Branch-wise Placements
- Internship Analysis
- Skill-wise Analysis
- Salary Distribution
- Location-wise Placements

---

## Tech Stack

### Business Intelligence

- Microsoft Power BI Desktop

### Data Processing

- Power Query

### Data Modeling

- Relationships
- Star Schema

### DAX Measures

- Placement %
- Average Salary
- Total Students
- Placed Students

### Data Source

- Microsoft Excel

---

## 📂 Project Structure

```text
College-Placement-Dashboard/
│
├── College Placement Dashboard.pbix
├── README.md
├── Screenshot 1.png
├── Screenshot 2.png
├── placement_data.xlsx

```

---

## 📊 Visualizations Used

- KPI Cards
- Clustered Bar Chart
- Pie Chart
- Donut Chart
- Area Chart
- Line Chart
- Scatter Plot
- Gauge Chart
- Table
- Slicers (Filters)

---

## 📈 DAX Measures

### Placement Percentage

```DAX
Placement % =
DIVIDE(
    COUNTROWS(
        FILTER(Data, Data[Status]="Placed")
    ),
    COUNTROWS(Data)
) * 100
```

### Average Salary

```DAX
Avg Salary =
AVERAGE(Data[Package])
```

### Total Students

```DAX
Total Students =
COUNTROWS(Data)
```

### Placed Students

```DAX
Placed Students =
CALCULATE(
COUNTROWS(Data),
Data[Status]="Placed"
)
```

---

## Dashboard Pages

### Page 1 – Placement Overview

- Placement KPIs
- Branch Analysis
- Student Status
- Internship Analysis
- CGPA vs Salary
- Placement Gauge
- Placement Trends

### Page 2 – Company Analysis

- Company-wise Hiring
- Industry Analysis
- Salary Analysis
- Skill Analysis
- Location-wise Placement
- Placement Comparison

---

## Project Objectives

- Analyze placement data efficiently
- Calculate placement percentage
- Monitor company hiring trends
- Compare branch performance
- Analyze salary distribution
- Study placement based on skills
- Provide interactive dashboards

---

## ⚙️ How to Open the Project

### Requirements

- Microsoft Power BI Desktop

### Steps

1. Clone the repository

```bash
git clone https://github.com/yourusername/College-Placement-Dashboard.git
```

2. Open

```
College Placement Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

3. Click

```
Refresh
```

to load the latest dataset.

---

## 📊 Dataset

The dashboard is created using placement-related data containing:

- Student Details
- Branch
- CGPA
- Internship
- Skills
- Company Name
- Salary Package
- Placement Status
- Placement Date
- Company Location

---

## 📈 Future Enhancements

- AI-based Placement Prediction
- Resume Analysis Dashboard
- Student Login System
- Real-time Database Integration
- Power BI Service Deployment
- Predictive Analytics
- Placement Recommendation System
- Interactive Web Dashboard

---

## 👩‍💻 Developed By

**Shrushti R. Handge**


---

## 📄 License

This project is developed for educational and academic purposes only.
