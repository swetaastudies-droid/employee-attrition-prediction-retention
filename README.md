# Employee Attrition Prediction & Retention Dashboard

## 📊 Project Overview

The **Employee Attrition Prediction & Retention Dashboard** is an HR Analytics project developed using **Microsoft Power BI** to analyse employee attrition patterns, identify employees with higher attrition risk, and evaluate potential retention strategies.

The project transforms employee-level HR data into an interactive dashboard that enables analysis across departments, job roles, tenure, performance, overtime, gender, salary, and training hours.

A **rule-based Attrition Risk Score (0–100)** is also developed to identify employees who may require greater retention attention.

---

## 🎯 Project Objectives

The key objectives of this project are to:

- Analyse overall employee attrition and workforce trends.
- Identify attrition patterns across departments and job roles.
- Analyse the relationship between attrition and employee characteristics.
- Examine the impact of tenure, overtime, performance rating, salary, and training hours.
- Develop a rule-based **Attrition Risk Score**.
- Categorise employees into **High, Medium, and Low Risk** levels.
- Identify employees with high attrition risk.
- Evaluate potential retention interventions using **What-If Analysis**.
- Present HR insights through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Microsoft Excel**
- **DAX**
- **Power BI What-If Parameters**
- **HR Analytics**
- **Data Visualization**

---

## 📁 Dataset

The project uses an employee dataset containing **200 employee records**.

### Key Variables

- Employee ID
- Department
- Job Role
- Tenure
- Salary
- Overtime
- Performance Rating
- Training Hours
- Age
- Gender
- Attrition

The dataset is provided in Excel format in this repository.

---

## 🔍 Attrition Analysis

The dashboard analyses employee attrition across multiple dimensions, including:

### Department
Analyses differences in employee attrition across departments.

### Job Role
Identifies attrition patterns across different employee roles.

### Tenure
Analyses attrition according to employee tenure groups:

- Less than 1 Year
- 1–2 Years
- 3–5 Years
- 6–10 Years
- 10+ Years

### Overtime
Examines attrition patterns among employees working overtime.

### Performance Rating
Analyses attrition based on employee performance ratings.

### Gender & Age
Provides demographic analysis of employee attrition.

---

# ⚠️ Attrition Risk Scoring

A rule-based **Attrition Risk Score ranging from 0 to 100** was developed using five employee-level conditions.

| Risk Factor | Score |
|---|---:|
| Tenure ≤ 2 years | +20 |
| Performance Rating ≤ 2 | +25 |
| Salary below department median | +15 |
| Overtime = Yes | +20 |
| Training Hours < 5 | +10 |

### Risk Categories

| Risk Score | Risk Category |
|---|---|
| 70+ | 🔴 High Risk |
| 40–69 | 🟠 Medium Risk |
| Below 40 | 🟢 Low Risk |

The scoring model provides a simple, transparent approach for identifying employees who may require greater retention attention.

---

## 📈 Dashboard

The Power BI dashboard provides interactive analysis through:

### Key Performance Indicators

- Total Headcount
- Employees Left
- Attrition Rate
- Average Tenure
- Overtime %
- Average Salary
- Average Performance Rating
- Average Training Hours
- High-Risk Employee Count

### Visualizations

The dashboard includes analysis of:

- Attrition by Department
- Attrition by Job Role
- Attrition by Gender
- Attrition by Tenure Group
- Attrition by Performance Rating
- Attrition by Overtime
- Salary Analysis
- Training Hours Analysis
- Performance Analysis
- High-Risk Employee List
- Training Hours vs Performance vs Attrition
- Scenario-based Risk Analysis

---

## 📊 Key Project Results

Based on the analysed dataset:

| Metric | Result |
|---|---:|
| Total Employees | 200 |
| Employees Left | 39 |
| Attrition Rate | 19.50% |
| Average Tenure | 4.28 years |
| Overtime | 30.50% |
| Average Salary | ₹731.16K |
| Average Performance Rating | 3.22 |
| Average Training Hours | 15.90 |
| High-Risk Employees | 3 |

### High-Risk Employees Identified

The rule-based model identified **3 employees** in the High Risk category:

- **EMP019** – Business Development Executive
- **EMP079** – HR Executive
- **EMP132** – Finance Executive

---

# 🔄 What-If Scenario Analysis

The project also includes **What-If Analysis** to evaluate potential changes in retention-related factors.

### Scenarios Analysed

#### 1. Training Increase
**Increase Training Hours by 20%**

#### 2. Salary Increase
**Increase salaries of low performers by 10%**

#### 3. Overtime Reduction
**Reduce overtime by 30%**

The scenarios were compared using the **Attrition Risk Score** and high-risk employee count.

### High-Risk Employee Count

| Scenario | High-Risk Employees |
|---|---:|
| Current | 3 |
| Training +20% | 3 |
| Salary +10% | 3 |
| Overtime -30% | 3 |

> **Note:** An attrition percentage reduction was not calculated because the project methodology does not define a direct conversion between the rule-based risk score and actual attrition probability.

---

## 💡 Retention Strategy Areas

Based on the analysis framework, the project focuses on three major retention strategy areas:

### 🎓 Training & Development
Review training requirements for employees with lower training exposure and provide relevant development opportunities.

### 💰 Salary Benchmarking
Review compensation levels, particularly where employee salary is below the department median.

### ⚖️ Workload Balancing
Monitor overtime and workload distribution to identify areas where workload balancing may support employee retention.

---

## 📷 Dashboard Preview

### Dashboard 1
![Dashboard 1](Dashboard%201.png)

### Dashboard 2
![Dashboard 2](Dashboard%202.png)

### Dashboard 3
![Dashboard 3](Dashboard%203.png)

---

## 📂 Repository Structure

```text
employee-attrition-prediction-retention/
│
├── Dashboard 1.png
├── Dashboard 2.png
├── Dashboard 3.png
│
├── Employee_Attrition_200_Records.xlsx
│
├── Employee_Attrition_Dashboard.pbix
│
├── Employee_Attrition_Retention_Report_Content_Only_Attractive.pptx
│
└── README.md
