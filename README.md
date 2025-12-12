# 📊 Power BI – HR Analytics Dashboard  
A complete end-to-end HR Analytics project built in **Power BI**, covering data cleaning, modeling, DAX, relationships, KPIs, and interactive dashboards.

This project helps HR teams monitor employee performance, attrition risk, demographics, and workforce trends.

---

## 🔍 Project Features
### ✅ 1. Data Cleaning & Transformation (Power Query)
- Removed nulls, blanks, duplicates  
- Unpivoted employee attributes  
- Created Dim tables (Department, JobRole, AgeGroup, Education, etc.)  
- Added Index-based surrogate keys  
- Generated FactEmployee table with cleaned + transformed structure  

---

## 🧱 Data Modeling (Star Schema)
- Central fact table: **FactEmployee_Unpivot**  
- Dimension Tables:
  - DimEmployee  
  - DimDepartment  
  - DimJobRole  
  - DimAgeGroup  
  - DimEducation  
- Relationships: **Many-to-One**, Single direction  
- Fully optimized star schema

---

## 🧮 DAX Measures
Key KPIs:
- **Total Employees**
- **Attrition Count**
- **Attrition Rate**
- **Average Age**
- **Average Salary**
- **High Risk Employees**
- **Performance Score**
- **YTD / MTD Measures**
- **Drillthrough-enabled KPI measures**

---

## 📈 Dashboard Pages
### **1️⃣ Overview Dashboard**
- Total Employees  
- Total Attrition + Attrition Rate  
- Avg Salary & Avg Age  
- Employees by Department  
- Employees by Education  
- Pie chart: Gender Split  
- Bar chart: Job Role Distribution  

### **2️⃣ Attrition Analysis**
- Attrition by Age Group  
- Attrition by Department  
- Attrition by Job Role  
- Attrition Trend  
- Drill-through to Employee Detail  

### **3️⃣ Performance Dashboard**
- High Risk Employees  
- Employees with Overtime  
- Performance vs Salary  
- Top & Bottom Performers  

### **4️⃣ Employee Detail (Drillthrough Page)**
- Complete employee profile  
- Salary, Overtime, Performance  
- Attendance & Work Hours  
- Employment history  

---

## 🎛️ Interactivity
- **Drillthrough** (right-click → Employee Detail)  
- **Drilldown** on charts   
- **Clear Filters button**  
- **Slicers** (Year, Department, Education, AgeGroup)

---

## 📦 Dataset
Dataset used: **Public HR Employee Data**  
Source: Open Data (HR Attrition Dataset)  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?utm_source=chatgpt.com
---

## 🛠 Tools Used
- Power BI Desktop  
- Power Query  
- DAX  
- Star Schema Modeling  

---

## 👨‍💻 Author
**Munir Hassan Usmani**  
Power BI Developer | Data Analyst  

---

## ⭐ Want to Support?
Give this repository a **star ⭐** if you find it useful!
