# Bangladeshi Student Survey – Data Processing & Analysis  

This repository contains code for cleaning, preprocessing, and analyzing survey data collected from Bangladeshi students.  
The main goal is to prepare a structured dataset that can be used for academic research, descriptive analysis, and visualization.  

---

##  Features  

###  Data Cleaning  
- Removes personally identifiable information (PII) such as names, emails, and institutions.  
- Normalizes column names into a consistent schema.  
- Handles missing or malformed GPA values and standardizes them.  

###  Data Transformation  
- Converts text/roman numerals for class levels into numeric format.  
- Extracts GPA values from mixed text formats.  
- Normalizes gender and other categorical fields.  

###  Validation & Filtering  
- Flags out-of-range values (e.g., GPA > 5.0).  
- Drops invalid rows to ensure dataset reliability.  

### Analysis & Visualization  
- Generates descriptive statistics for numerical and categorical data.  
- Saves cleaned dataset as **`preprocessed_student_data.csv`**.  
- Produces distribution plots (class, gender, study hours, etc.) and trend charts for GPA.  
- Exports summary tables (**`numeric_summary.csv`**, **`class_distribution.csv`**).  

---

##  Requirements  

Make sure you have the following Python libraries installed:  

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
```
---
[![DOI](https://zenodo.org/badge/1067838694.svg)](https://doi.org/10.5281/zenodo.17244015)
