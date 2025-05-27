# Titanic Survival Analysis

This project involves end-to-end processing and analysis of Titanic passenger data, focusing on understanding survival factors using structured data transformation and statistical analysis. It demonstrates foundational data engineering tasks such as data cleaning, feature engineering, and efficient exploratory data analysis.

---

## Dataset Overview

- **Source**: Kaggle Titanic Dataset  
- **Primary File Used**: `train.csv`  
- **Records**: 891 passengers  
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

---

## Key Steps

### 1. Data Cleaning
- Imputed missing `Age` values with the **median**
- Filled missing `Embarked` entries with the **mode**
- Dropped `Cabin` due to excessive missing data
- Verified dataset had **no duplicate records**

### 2. Feature Engineering
- Created an `Age Group` feature: Child, Adult, Senior
- Retained essential features relevant to survival prediction

### 3. Exploratory Analysis
- Analyzed distributions of key variables (`Age`, `Fare`)
- Compared survival rates by `Gender`, `Class`, and `Age Group`
- Conducted a **T-test** to validate gender impact on survival

---

## Tools & Technologies

- Python (Pandas, NumPy, SciPy)
- Visualization: Matplotlib, Seaborn
- Jupyter Notebook for execution and documentation

---

## Files

- `Source_code.ipynb`: Complete implementation
- `README.md`: Project summary

---

## Purpose

This project reflects core skills in:
- Data preprocessing and wrangling
- Data profiling and integrity checks
- Deriving insights through structured exploration

