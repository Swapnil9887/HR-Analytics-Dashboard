
# HR Analytics Dashboard using Power BI 

## Objective
The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization. This dashboard offers a detailed analysis of employee attrition, empowering the HR team with data-driven insights for better decision-making.

---

## Key Features
- **Dive deep into HR data** to uncover valuable insights.
- **Develop interactive dashboards** to visualize key HR metrics.
- **Provide actionable recommendations** for strategic decision-making.

---

## Steps Followed

### 1. Data Gathering
- Imported raw `.csv` data into Power BI.
- Transformed the data using Power Query Editor for cleaning and processing.

### 2. Data Cleaning
- Removed empty columns, duplicates, and errors.
- Renamed and standardized column values.
- Detected and corrected data types using the Auto Detect function.

### 3. Data Processing
- Created a new column, **"AttritionCount"**, using the Conditional Column feature (`IF Attrition = 'Yes' THEN 1 ELSE 0`).
- Created measures using DAX queries:
  - **Attrition Rate** = `(SUM([AttritionCount])/SUM([EmployeeCount])) * 100`
- Used these metrics to create various KPIs and charts.

### 4. Data Analysis
- Designed visualizations like bar charts, KPIs, tables, pie charts, and more to present data in a clear and interactive format.

---

## Key Dashboard Questions
1. **What is the Total Employee Count?**
2. **What is the employees' Average Age & Average Salary?**
3. **What is the Attrition Count of men and women?**
4. **What are the employees' Working Years at the Company?**
5. **Which Department has the maximum employees?**
6. **What is the Gender distribution?**
7. **Which Education Field has the maximum employees?**
8. **Which Business Travel type has the maximum employees?**

---

## Tools & Techniques Learned
- **Calculated Field**: Used to calculate Attrition Rate & Active Employees.
- **Matrix Table**: Displayed Job Satisfaction ratings.
- **Visualizations**: 
  - Donut Chart
  - Pie Chart
  - Bar Chart
  - Cluster Chart 📊
- **KPIs**: Key Performance Indicators and Slicers.
- **Filters**: Applied to data for insights by education field and more.

---

## Key Insights Summary
- **Total Employees**: The organization has grown to **1470 employees**, showcasing significant growth.
- **Attrition Analysis**:
  - Total attrition: **237 employees**.
  - Males: **150**, Females: **87** — Higher attrition among males.
- **Departmental Attrition**:
  - Research & Development experienced the highest attrition rate (**56.13%**).
- **Education Field Impact**:
  - Life sciences employees showed the highest attrition rate.
- **Job Role Affected**:
  - Sales roles had the highest attrition, indicating a need for targeted retention strategies.
- **Education-wise Attrition**:
  - High School education level had the highest attrition rate (**18.24%**).
- **Attrition by Age Group**:
  - Employees aged **25-34 years** had the highest attrition count (**112 employees**).

---

## Visualizations Used
1. **Bar Charts**: For department-wise attrition analysis.
2. **Pie & Donut Charts**: For gender and education distribution.
3. **KPI Cards**: To display overall metrics like Total Employees and Attrition Rate.
4. **Matrix Tables**: To show job satisfaction ratings.
5. **Filters & Slicers**: For interactive data filtering.

---



