"""# 📊 Income vs Education Level Analysis
**CSE 578 – Data Visualization Project**  
**Author**: Jerry Barboza

---

## 📝 Overview

This project explores how **education level, race, occupation, and relationship status** relate to income levels using the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult). Through visualizations and exploratory data analysis, we uncover which factors are most associated with earning over $50K per year.

---

## 📁 Dataset

- **Source**: [UCI Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult)
- **Records**: 32,561 entries (after cleaning)
- **Features Used**:
  - Age
  - Education
  - Occupation
  - Race
  - Relationship
  - Salary
  - Hours per Week
  - Capital Gain/Loss

---

## 🎯 Goals

- Understand how **education** affects the probability of earning >$50K.
- Compare **race** and **occupation** distributions across income levels.
- Analyze **work hours** by relationship status using parallel coordinate plots.

---

## 🔧 Technologies Used

- `pandas` – data cleaning & transformation  
- `matplotlib` – bar, pie, and parallel plots  
- `numpy` – numerical operations

---

## 📊 Visualizations

| Visualization Type | Description |
|--------------------|-------------|
| **Correlation Matrix** | Shows how strongly each numeric feature (age, education level, etc.) correlates with salary. |
| **Bar Charts** | Compares education frequencies for >$50K vs <=$50K groups. |
| **Pie Charts** | Displays race and occupation proportions by salary group. |
| **Parallel Coordinates** | Explores hours worked per week by education and relationship groups. |

---

## 📌 Key Insights

- Individuals with **Prof-school** and **Doctorate** degrees are **3x more likely** to earn over $50K.
- **Exec-managerial** and **prof-specialty** roles are more common among high earners.
- Most workers in the <=$50K group hold roles like **handlers-cleaners** or **machine-operators**.
- People working >50 hours/week tend to have **higher education levels** and **spousal relationships**.

---
