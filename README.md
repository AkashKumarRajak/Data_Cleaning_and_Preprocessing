# Elevate-Labs-Task_1
# 🧹 Task 1: Data Cleaning and Preprocessing

**Internship**: Data Analyst Intern  
**Company**: Elevate Labs  
**Date**: 2/June/2025  
**Intern**: Akash Kumar Rajak

---

## 📄 Dataset Used

- **Name**: Medical Appointment No Shows  
- **Source**: [Kaggle - No Show Appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)  
- **Rows/Columns**: 110,527 rows and 14 columns  
- **Objective**: Clean and preprocess the raw dataset to prepare it for further analysis or modeling.

---

## 🔧 Tools & Libraries

- **Language**: Python  
- **Environment**: Jupyter Notebook  
- **Libraries**:  
  - `pandas` for data manipulation  
  - `datetime` for handling date types  
  - `fpdf` for PDF report generation  
  - `matplotlib` and `seaborn` (optionally for future visualization tasks)

---

## 🧼 Data Cleaning Steps

1. **Loaded** the dataset using Pandas.
2. **Checked for missing values** using `.isnull().sum()`.
3. **Removed duplicates** using `.drop_duplicates()`.
4. **Standardized text values** in columns like `Gender` and `No-show` (uppercased).
5. **Converted date columns** (`ScheduledDay`, `AppointmentDay`) to `datetime` objects.
6. **Renamed columns** to lowercase with underscores for consistency.
7. **Corrected data types** (e.g., age, scholarship, etc., converted to integer).
8. **Removed invalid records**, such as entries with negative age values.
9. **Exported** the cleaned dataset to `cleaned_noshowappointments.csv`.

---

## 📁 Files Included

| File Name                          | Description                              |
|-----------------------------------|------------------------------------------|
| `noshowappointments.csv`          | Original raw dataset                     |
| `cleaned_noshowappointments.csv`  | Final cleaned version                    |
| `Task1_DataCleaning.ipynb`        | Jupyter Notebook with full code & output |
| `Data_Cleaning_Task1_Report.pdf`  | PDF summary report of this task          |
| `README.md`                       | This file (task documentation)           |

---

## 📊 Summary of Changes

- No missing values were found.
- 100+ duplicate rows removed.
- Inconsistent text formatting standardized.
- Dates converted to consistent `datetime` format.
- Column names cleaned for readability.
- Negative ages removed as invalid data.
- Final cleaned dataset saved and exported.

---

## ✅ Deliverables

- ✅ Cleaned dataset
- ✅ Jupyter notebook with all steps and comments
- ✅ PDF report summarizing task
- ✅ README file for documentation

---

## 📬 Contact

For any questions, feel free to reach out.

