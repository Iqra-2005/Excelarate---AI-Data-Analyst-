# 📊 Excelerate Internship Project – SLU Opportunity Data Analysis

This repository contains the code and analysis I completed during my internship at **Excelerate**, focused on cleaning, transforming, and enriching a real-world dataset related to student opportunities.

## 📁 Project Overview

The notebook demonstrates the **end-to-end data processing pipeline** applied to the **SLU Opportunity Wise dataset**, including:

## 🚀 Key Tasks Completed

### ✅ Data Cleaning
- Filled missing values in fields like `Institution Name` and `Apply Date`
- Coerced invalid date formats into `NaT` safely
- Standardized formats for:
  - Gender (`M`, `F`, `female` → `Male`, `Female`, etc.)
  - Strings (title case, stripped spaces)
  - Institutions (e.g., “St. Louis” → “Saint Louis”)

### ✅ Feature Engineering
- **Age** (calculated from `Date of Birth`)
- **Engagement Duration** = `Apply Date` − `Opportunity Start Date`
- **Time in Opportunity** = `Opportunity End Date` − `Opportunity Start Date`
- **Signup Month** and **Signup Year** (extracted from datetime)
- **Gender Binary Encoding**: `Male` = 1, `Female` = 0, `Other` = -1
- **MinMax Normalization** of numerical features

### ✅ Exploratory Data Analysis (EDA)
- 

## 🧰 Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **scikit-learn** (for preprocessing)

---

## 📂 Files in This Repository

| File Name                             | Description                                      |
|--------------------------------------|--------------------------------------------------|
| `excelerate internship codfile.ipynb` | Main notebook with full data cleaning and feature engineering , ML mddel training and testing and building a simple recommendation system. |
| `README.md`                          | Project overview and documentation (this file)   |

---



## 🙌 Acknowledgements

This work was completed as part of my internship at **Excelerate**, under guidance from the data team. Special thanks to the project mentors for their support.

---

