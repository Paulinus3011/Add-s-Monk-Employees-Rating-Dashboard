# Add-s-Monk-Employees-Rating-Dashboard

# Employees Rating Dashboard  

This repository contains a Power BI dashboard analyzing the **performance ratings of employees** across the organization.  
It highlights total employees, overall rating distribution, and breakdowns by **gender**, **region**, and **department**.  

---

##  Objective  

The goal of this dashboard is to:  
- Evaluate the **distribution of employee performance ratings**.  
- Compare ratings by **gender**, **region**, and **department**.  
- Identify areas with higher proportions of **good/very good ratings** vs. **poor/very poor ratings**.  
- Provide insights for performance management and HR decision-making.  

---

##  Dataset Summary  

- **Total Employees:** 869  
- **Rating Categories:**  
  - **Average:** 419 employees  
  - **Good:** 180 employees  
  - **Poor:** 129 employees  
  - **Very Good:** 87 employees  
  - **Very Poor:** 54 employees  

---

## 📖 Data Dictionary  

| **Field Name**       | **Description**                                               | **Example Values**     |
|-----------------------|---------------------------------------------------------------|------------------------|
| **EmployeeID**        | Unique identifier for each employee.                          | 001, 002, 003          |
| **Gender**            | Employee gender classification.                               | Male, Female           |
| **Department**        | Department to which the employee belongs.                     | HR, Sales, Support, Finance |
| **Location**          | Region/office where the employee is based.                    | Texas, Florida, Mississippi |
| **Rating**            | Performance rating of the employee.                           | Average, Good, Poor, Very Good, Very Poor |
| **NoOfEmployees**     | Count of employees per rating/attribute (aggregated measure). | 869                    |

---

##  Data Source  

The dataset used in this dashboard was obtained from a **Power BI training/tutorial dataset** designed for practice and demonstration purposes.  

- **Type:** Sample HR/Employee dataset  
- **Format:** Excel file (imported into Power BI)  
- **Fields Included:** Employee ID, Gender, Department, Location, Rating  
- **Usage:** For **educational and analytical demonstration**.  

  

---

## 📊 Dashboard Insights  

### 1. Overall Rating Distribution  
- **Average** ratings dominate with **419 employees (48.2%)**.  
- **Good:** 180 employees (20.7%).  
- **Poor:** 129 employees (14.8%).  
- **Very Good:** 87 employees (10%).  
- **Very Poor:** 54 employees (6.2%).  

 **Insight:** Nearly half of employees fall under the **average rating category**, showing room for performance improvement initiatives.  

---

### 2. Rating Breakdown by Gender  
- **Average Ratings:** Male – 220 | Female – 199  
- **Good Ratings:** Male – 86 | Female – 94  
- **Poor Ratings:** Male – 58 | Female – 71  
- **Very Good Ratings:** Male – 50 | Female – 37  
- **Very Poor Ratings:** Male – 20 | Female – 34  

 **Insight:**  
- Males dominate in **average and very good ratings**.  
- Females are higher in **good ratings** but also slightly higher in **poor and very poor ratings**.  

---

### 3. Rating Breakdown by Region  
- **Texas:** Average (172), Good (67), Poor (47), Very Good (27), Very Poor (23).  
- **Florida:** Average (136), Good (70), Poor (47), Very Good (39), Very Poor (17).  
- **Mississippi:** Average (53), Good (21), Poor (22), Very Good (18), Very Poor (15).  
- **Los Angeles:** Average (29), Good (17), Poor (9).  
- **Carifonia & Carrifornia:** Very small representation.  

 **Insight:**  
- Texas and Florida are the largest hubs with the highest rating distributions.  
- Florida shows relatively more **very good ratings (39)** compared to Texas.  
- Mississippi has a higher share of **poor ratings** relative to its size.  

---

### 4. Rating Breakdown by Department  
- **Most departments** show a mix of ratings, with **average** dominating.  
- Examples:  
  - **Product Dept:** Average (17), Good (9), Poor (6), Very Good (7), Very Poor (4).  
  - **HR Dept:** Average (41), Good (18), Poor (14), Very Good (10), Very Poor (9).  
  - **Research:** Balanced distribution with significant **good and very good ratings**.  

 **Insight:** Performance distribution varies slightly by department, but no extreme outliers exist.  

---

##  Conclusion  

- **Nearly half (48.2%) of employees are rated average**, which highlights a potential **performance development opportunity**.  
- **Gender:** Male employees tend to dominate in **average and very good ratings**, while females are slightly stronger in **good ratings** but also have more poor/very poor ratings.  
- **Regions:** Texas and Florida are the main hubs, with Florida showing stronger **very good ratings** compared to Texas.  
- **Departments:** Distribution is mostly balanced, with HR and Research showing encouraging **good/very good performance levels**.  

Overall, the organization maintains a **diverse rating distribution**, but there is a clear opportunity to **lift employees out of the average category** through targeted training and performance management strategies.  

---

##  Tools Used  

- **Power BI** → Data modeling & visualization  
- **Dataset** → Employee records (Gender, Region, Department, Ratings)  

---

##  Next Steps  

- Analyze **time trends** in performance ratings.  
- Compare ratings by **experience level or job role**.  
- Link ratings with **training participation** or **productivity metrics**.  
- Build a predictive model to identify **factors influencing performance ratings**.  

---
