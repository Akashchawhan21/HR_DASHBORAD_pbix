# 📊 HR Analytics Dashboard — Power BI

An interactive **HR Analytics Dashboard** built using **Microsoft Power BI** to analyze employee data, workforce demographics, attrition, salary distribution, job roles, and other key HR metrics.

The dashboard transforms raw HR data into meaningful visual insights that can help organizations understand their workforce and make data-driven HR decisions.

---

## 🚀 Project Overview

The **HR Dashboard** provides a comprehensive view of an organization's workforce through interactive reports and visualizations.

It focuses on important HR metrics such as:

* 👥 Total Employees
* 📉 Employee Attrition
* 📊 Attrition Rate
* 🎂 Employee Age Distribution
* ⚧️ Gender Distribution
* 💼 Job Role Analysis
* 💰 Salary Analysis
* 🏢 Department-wise Workforce
* 🎓 Education Analysis
* ⏳ Employee Experience
* 📍 Employee Demographics

The dashboard allows users to interact with different filters and explore employee information from multiple perspectives.

---

## 🛠️ Tools & Technologies

| Tool                   | Purpose                                 |
| ---------------------- | --------------------------------------- |
| **Microsoft Power BI** | Dashboard development & visualization   |
| **Power Query**        | Data cleaning & transformation          |
| **DAX**                | Calculated measures and KPIs            |
| **Excel / CSV**        | Source HR dataset                       |
| **GitHub**             | Project documentation & version control |

---

## 📌 Key KPIs

The dashboard includes important HR Key Performance Indicators such as:

* **Total Employees**
* **Total Attrition**
* **Attrition Rate**
* **Average Employee Age**
* **Average Salary**
* **Average Years at Company**
* **Employee Count by Department**
* **Employee Count by Job Role**

These KPIs provide a quick overview of the organization's workforce.

---

## 📈 Dashboard Insights

### 👥 Workforce Analysis

Analyze the overall employee population based on:

* Department
* Job Role
* Gender
* Education
* Age
* Experience

### 📉 Attrition Analysis

Understand employee turnover through:

* Overall attrition rate
* Attrition by department
* Attrition by job role
* Attrition by age group
* Attrition by gender
* Attrition by experience

### 💰 Salary Analysis

Explore salary patterns across:

* Departments
* Job roles
* Employee experience
* Education levels
* Age groups

### 📊 Employee Demographics

The dashboard provides demographic insights using:

* Age groups
* Gender
* Education
* Marital status
* Job roles
* Departments

---

## 🎨 Dashboard Features

* Interactive Power BI visuals
* KPI cards
* Slicers and filters
* Dynamic charts
* Department-level analysis
* Attrition analysis
* Employee demographic analysis
* Salary analysis
* User-friendly dashboard design

---

## 📂 Project Structure

```text
HR-Analytics-Dashboard/
│
├── HR_DASHBOARD.pbix
├── README.md
│
└── screenshots/
    └── dashboard.png
```

> **Note:** The `.pbix` file is the main Power BI project file.

---

## 🔄 Data Preparation

The HR dataset was prepared using **Power Query** before building the dashboard.

The data preparation process included:

1. Loading the HR dataset into Power BI
2. Checking column names and data types
3. Removing unnecessary data
4. Handling missing values
5. Transforming columns where required
6. Creating useful categories such as age groups
7. Preparing the dataset for visualization
8. Creating DAX measures for dashboard KPIs

---

## 🧮 DAX & Calculations

The dashboard uses **DAX (Data Analysis Expressions)** to create calculated metrics and KPIs.

Examples include:

```DAX
Total Employees = COUNTROWS(EmployeeData)
```

```DAX
Total Attrition =
CALCULATE(
    COUNTROWS(EmployeeData),
    EmployeeData[Attrition] = "Yes"
)
```

```DAX
Attrition Rate =
DIVIDE(
    [Total Attrition],
    [Total Employees],
    0
)
```

> The exact measures may vary depending on the dataset and dashboard implementation.

---

## 💡 Business Questions Answered

This dashboard can help answer questions such as:

* How many employees are currently in the organization?
* What is the overall employee attrition rate?
* Which departments have higher attrition?
* Which job roles have the highest employee count?
* How does salary vary across different job roles?
* Which age groups have higher attrition?
* How does employee experience relate to attrition?
* What is the gender distribution?
* What is the average employee salary?
* Which departments have the largest workforce?

---

## 📷 Dashboard Preview

Add your Power BI dashboard screenshot here:

```markdown
![HR Dashboard](screenshots/dashboard.png)
```

---

## ▶️ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/your-username/HR-Analytics-Dashboard.git
```

### 2. Open the project

Open:

```text
HR_DASHBOARD.pbix
```

using **Microsoft Power BI Desktop**.

### 3. Explore the dashboard

Use the available:

* Filters
* Slicers
* Charts
* KPI cards
* Interactive visuals

to explore the HR data.

---

## 📊 Skills Demonstrated

This project demonstrates practical knowledge of:

* Power BI
* Data Visualization
* Data Cleaning
* Power Query
* DAX
* KPI Development
* Business Intelligence
* HR Analytics
* Data Analysis
* Dashboard Design
* Interactive Reporting

---

## 🎯 Project Objective

The primary objective of this project is to demonstrate how **Power BI can transform raw HR data into an interactive business intelligence dashboard**.

The dashboard helps convert employee data into actionable insights related to **workforce composition, attrition, salary, demographics, and employee experience**.

---

## 👨‍💻 Author

**Akash Chawhan**

BCA Student | Data Analytics Enthusiast

### Areas of Interest

* Data Analytics
* Power BI
* Python
* SQL
* Data Visualization
* Business Intelligence

---

## ⭐ If You Like This Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📜 License

This project is created for **educational and portfolio purposes**.
