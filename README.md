# Healthcare Dataset EDA With PYTHON

This project explores a synthetic healthcare dataset using Python for **Exploratory Data Analysis (EDA)**. The goal is to derive insights about patients, hospital stays, medical conditions, billing trends, and insurance providers through various visualizations and statistical summaries.

---

## 🔧 Tools & Libraries Used

* **Python** (Pandas, NumPy) for data manipulation
* **Matplotlib & Seaborn** for static plots
* **Plotly** (optional in notebook) for interactive charts

---

## 📂 Dataset Overview

* The dataset includes columns such as: `Name`, `Age`, `Gender`, `Blood Type`, `Medical Condition`, `Admission Type`, `Date of Admission`, `Discharge Date`, `Billing Amount`, `Hospital`, `Doctor`, and `Insurance Provider`.
* Dataset was cleaned by removing missing and duplicate rows, and converting data types appropriately.

---

## 📋 Key Data Preparation Steps

* Cleaned and standardized patient names.
* Converted `Date of Admission` and `Discharge Date` to datetime format.
* Created a new column `Days Hospitalized` to calculate hospital stay duration.
* Adjusted billing amounts by converting all values to positive.

---

## 📊 Statistical Analysis

### ✅ Descriptive Statistics

* Generated summary statistics for numeric and categorical variables.
* Identified null values and duplicates for cleanup.
* Displayed distributions of variables like gender, age, admission types, and test results.

### ⚖️ Hospital Stay Analysis

* Calculated the minimum, maximum, and average length of hospital stay by medical condition.
* Visualized hospital stay durations per condition.

### 💸 Billing Insights

* Grouped billing amounts by `Medical Condition`, `Hospital`, `Doctor`, and `Insurance Provider`.
* Analyzed minimum, maximum, and average billing amounts.
* Highlighted top 10 hospitals and top 20 doctors by total billing.

### 📅 Time Analysis

* Analyzed admissions and discharges by month.
* Determined monthly trends in patient conditions.

---

## 👥 Demographics Analysis

* Analyzed gender distribution with count and percentage.
* Visualized age trends across medical conditions.
* Compared billing amounts for male vs female patients by condition.

---

## 📊 Visualizations Included

* Pie charts: Gender, Blood Type, Admission Type, Insurance Provider, Test Results
* Bar charts: Top hospitals and doctors by billing, gender/condition comparison
* Line charts: Trends of average age, billing, and hospital stay per condition
* Grouped visualizations: Gender-wise condition counts, Monthly condition trends

---

## 📆 Outcomes & Learnings

* Found insightful patterns in billing, gender, age, and condition-specific trends.
* Identified top contributors (hospitals/doctors) to healthcare costs.
* Gained hands-on experience in real-world healthcare data cleaning and visualization.

---

## 💾 Project Structure

```
healthcare_eda/
├── healthcare_dataset.csv
├── healthcare_eda.ipynb
├── README.md
```
