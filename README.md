# Placement Trend Analysis (2020–2024)

## Project Overview

This project analyzes five years of college placement data (2020–2024) to identify trends in student hiring, salary growth, company participation, and branch-wise performance.

The dashboard is built in **Power BI** and focuses on delivering actionable insights for the college placement cell and academic leadership.

---

## Business Objective

The primary objective of this project is to answer:

* How has placement performance changed over the last 5 years?
* Which branches have the highest placement rates?
* Which companies offer the highest salary packages?
* Is there year-over-year salary growth?
* What patterns can help improve placement outcomes?

---

## Key KPIs Tracked

* Placement Rate (%)
* Average Salary
* Highest Package
* Total Companies Visited
* Branch-wise Placement %
* Year-over-Year Salary Growth
* Trend Analysis (2020–2024)

---

## Dataset Information

The project uses structured Excel datasets including:

* Placement Data (2020–2024)
* Company Lookup Table
* Student Lookup Table
* Calendar Dimension Table
* Region Lookup Table

Data was cleaned and transformed before modeling.

### Data Cleaning Steps:

* Removed duplicate student records
* Standardized branch names
* Converted salary values to numeric format
* Handled missing package values
* Created proper date hierarchy using calendar table

---

## Tools & Technologies Used

* **Power BI**
* **DAX (Data Analysis Expressions)**
* **Excel**
* Data Modeling (Star Schema)
* Relationship Management
* KPI & Dashboard Design

---

## Data Modeling Approach

The project follows a **star schema design**:

Fact Table:

* Placement Data

Dimension Tables:

* Calendar
* Company
* Student
* Region

This improves performance and enables accurate time-based and categorical analysis.

---

## Key Insights

* Placement rate shows consistent improvement from 2020 to 2024.
* Post-COVID years show strong salary recovery.
* A small number of companies contribute a large share of total offers.
* Technical branches demonstrate higher average packages.
* Year-over-year growth indicates improving industry engagement.

---

## 📂 Repository Structure

```
placement-analytics-dashboard/
│
├── datasets/            # Raw datasets (Excel files)
├── Dashboard/           # Power BI .pbix file
├── Screenshots/         # Dashboard images
└── README.md            # Project documentation
```

---

## Skills Demonstrated

* Business problem structuring
* Data cleaning & preprocessing
* Data modeling (Star Schema)
* DAX calculations
* KPI design
* Data storytelling
* Dashboard UI/UX design

---

## 👨‍💻 Author

Abhay Kumar Mandal

---

