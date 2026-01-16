# AI & ML Internship – Task 2  
## Data Cleaning & Missing Value Handling

---

## 📌 Task Objective
The objective of **Task 2** is to perform data cleaning and handle missing values effectively. This task focuses on identifying missing data, visualizing missing value patterns, applying appropriate imputation techniques, validating cleaned datasets, and preparing data for machine learning.

---

## 🛠 Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  
- GitHub  

---

## 📊 Datasets Used

### 1️⃣ House Prices Dataset
- Notebook: `Task2_House_Prices_Data_Cleaning.ipynb`
- Dataset Source: Created and loaded programmatically inside the notebook
- Files:
  - `house_prices_raw.csv`
  - `house_prices_cleaned.csv`

**Dataset Details:**
- Numerical Features: `LotArea`, `OverallQual`, `YearBuilt`, `TotalBsmtSF`, `SalePrice`
- Categorical Features: `GarageType`, `FireplaceQu`

**Missing Value Handling:**
- Numerical columns were imputed using **median**
- Categorical columns were imputed using **mode**
- Columns with extremely high missing values were removed
- Dataset was validated after cleaning

---

### 2️⃣ Medical Appointment No Shows Dataset
- Notebook: `Task2_Medical_Appointment_Data_Cleaning.ipynb`
- Dataset Source: Created and loaded programmatically inside the notebook
- Files:
  - `medical_appointments_raw.csv`
  - `medical_appointments_cleaned.csv`

**Dataset Details:**
- Numerical Features: `Age`, `Scholarship`, `Hypertension`, `Diabetes`, `SMS_received`
- Categorical Features: `Gender`, `Neighbourhood`, `No_show`

**Missing Value Handling:**
- Numerical columns were imputed using **median**
- Categorical columns were imputed using **mode**
- Dataset was validated to ensure no missing values remained

---

## 🔍 Steps Performed
1. Loaded datasets and identified missing values using `isnull().sum()`
2. Visualized missing value patterns using bar charts
3. Applied median imputation for numerical features
4. Applied mode imputation for categorical features
5. Removed columns with extremely high missing values
6. Validated datasets after cleaning
7. Compared dataset size before and after cleaning
8. Saved cleaned datasets for further machine learning tasks

---

## 📈 Final Outcome
- Gained hands-on experience in data cleaning and preprocessing
- Learned effective strategies for handling missing data
- Improved understanding of data quality and its importance
- Prepared clean, machine-learning-ready datasets
