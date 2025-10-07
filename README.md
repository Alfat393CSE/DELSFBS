# 🎓 A Dataset on Educational, Lifestyle, and Socioeconomic Factors of Bangladeshi Students (DELSFBS)

[![DOI](https://zenodo.org/badge/1067838694.svg)](https://doi.org/10.5281/zenodo.17244015)  
*A comprehensive workflow for cleaning, transforming, and analyzing survey data collected from Bangladeshi students.*

---

## 📘 Overview  

This repository contains Python scripts for **data preprocessing, validation, and visualization** of student survey responses.  
The main goal is to prepare a **structured, research-ready dataset** suitable for statistical analysis, educational studies, and academic publications.

---

## ✨ Features  

### 🧹 Data Cleaning  
- Removes **personally identifiable information (PII)** such as names, emails, and institutions.  
- Normalizes column names into a consistent schema.  
- Handles missing or malformed **GPA values** and standardizes them.  

### 🔄 Data Transformation  
- Converts **text or Roman numerals** for class levels into numeric format.  
- Extracts **GPA values** from mixed text fields.  
- Normalizes **gender and other categorical attributes** for uniformity.  

### ✅ Validation & Filtering  
- Flags **out-of-range values** (e.g., GPA > 5.0).  
- Drops invalid or inconsistent rows to ensure dataset reliability.  

### 📊 Analysis & Visualization  
- Generates **descriptive statistics** for both numerical and categorical data.  
- Saves the cleaned dataset as **`preprocessed_student_data.csv`**.  
- Produces **distribution plots** (class, gender, study hours, etc.) and **trend charts for GPA**.  
- Exports **summary tables** such as `numeric_summary.csv` and `class_distribution.csv`.  

---

## ⚙️ Requirements  

Before running the scripts, make sure the following Python libraries are installed:  

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
```
---
##  License

This project is provided for educational and research purposes.
You are free to use and adapt it with proper attribution.

