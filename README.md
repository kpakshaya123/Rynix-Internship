# Rynix-Internship
# 📊 Intern Performance Analytics & Insights Dashboard

## 🚀 Project Overview

The **Intern Performance Analytics & Insights Dashboard** is a data-driven project designed to evaluate and analyze intern performance based on key metrics such as attendance, task completion, and performance scores.

This project helps in making **data-driven decisions** for hiring, stipends, and performance evaluation.

---

## 🎯 Objectives

* Analyze intern performance using structured data
* Automate calculation of attendance and task completion
* Generate performance scores and status
* Provide hiring recommendations based on performance
* Visualize insights using dashboards

---

## 📂 Dataset Details

The dataset includes the following fields:

* Intern ID
* Name
* Email ID
* Gender
* Phone Number
* Domain
* Date Range
* Total Days
* SOD Filled
* EOD Filled
* Attendance (%)
* Task Scores (Task 1–4)
* Task Completion (%)
* Performance Score
* Performance Status
* Stipend
* Hiring Recommendation

---

## 📈 Key Calculations

### 🔹 Attendance %

```
((SOD Filled + EOD Filled) / 2) / Total Days * 100
```

### 🔹 Task Completion %

```
(Completed Tasks / Total Tasks) * 100
```

### 🔹 Performance Score

```
Average of Task Scores
```

---

## 💡 Hiring Logic

* ₹15,000 → Hire as Employee
* ₹10,000 → Intern (6 Months)
* ₹0 → Intern (1 Month / No Stipend)

---

## 🛠️ Tools & Technologies

* Python (Pandas)
* Google Colab
* Excel
* Power BI (Data Visualization)

---

## 📊 Features

* Automated performance calculation
* Clean and structured dataset
* Insight generation for decision-making
* Easy-to-understand metrics

---

## 🙌 Conclusion

This project helps mentors analyze intern performance and guide hiring decisions using data analytics.
