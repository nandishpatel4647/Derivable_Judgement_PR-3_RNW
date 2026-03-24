# 📊 Statistical Analysis Project using Python

This project demonstrates basic statistical analysis using Python on a health dataset.  
It includes concepts like confidence intervals, hypothesis testing, and correlation using simple and beginner-friendly code.

---

## 📁 Dataset

- File: `health_dataset_id_101_180_records.csv`
- Total Records: 180
- Record IDs: Start from 101
- Features:
  - age, age_group
  - gender, region
  - weight, bmi
  - smoking_status, exercise_frequency
  - blood_pressure
  - diabetes, hypertension
  - cholesterol_level, glucose_level
  - visit_date

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Jupyter Notebook

---

## 📌 Tasks Performed

### 1. Data Loading
- Imported dataset using Pandas
- Displayed first few rows

### 2. Descriptive Statistics
- Calculated mean values of Age and BMI

### 3. Confidence Interval
- Computed 95% confidence interval for Age

### 4. Z-Test
- Tested whether average BMI differs from assumed value (25)

### 5. T-Test
- Compared BMI between Male and Female groups

### 6. Chi-Square Test
- Checked relationship between smoking and diabetes

### 7. ANOVA Test
- Compared BMI across different age groups

### 8. Correlation
- Measured relationship between Age and BMI

---

## ▶️ How to Run

1. Open Jupyter Notebook
2. Place the dataset file in the same folder
3. Run the cells step by step

---

## 📌 Sample Code

```python
import pandas as pd

df = pd.read_csv("health_dataset_id_101_180_records.csv")
print(df.head())
