
# Lung Cancer Patient Health and Treatment Records - PySpark Tasks

This document outlines the tasks to be performed using PySpark on the **Lung Cancer Patient Health and Treatment Records** dataset. The dataset includes detailed information on patient demographics, diagnosis stage, lifestyle risk factors, comorbidities, and treatment outcomes.

---

## Task 1: Data Cleaning

Write a function that:
- Removes duplicate rows.
- Ensures correct data types for numerical and date columns.
- Converts all ‘yes’/‘no’ type fields into 1/0 format.

---

## Task 2: Treatment Duration Analysis

Write a function that:
- Adds a new column, `treatment_duration_days`, which calculates the number of days between the diagnosis and the end of treatment.
- Returns the average treatment duration for each treatment type.

---

## Task 3: Survival Rate by Smoking Status

Write a function that:
- Returns the `smoking_status` group with the highest survival rate.

---

## Task 4: Stage IV Diagnosis by Country

Write a function that:
- Returns the top three countries with the highest percentage of patients diagnosed in Stage IV.

---

## Task 5: Complex Filtering and Aggregation

Write a function that filters patients who:
- Are male.
- Diagnosed in Stage III or IV.
- Have a family history of cancer.
- Are current smokers.
- Have a BMI > 30.
- Survived.

Then return:
- The average age of these patients.
- The percentage of these patients who had hypertension.

---

**End of Tasks**