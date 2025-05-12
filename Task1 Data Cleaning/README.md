# Task 1 – Data Cleaning and Preprocessing

## 🎯 Objective
To clean and prepare a raw dataset by handling missing values, duplicates, and inconsistent formatting using Python (Pandas) in Jupyter Notebook.

---

## 📂 Dataset
- **Source:** [Kaggle – Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation)
- **Original File:** `Mall_Customers.csv`
- **Cleaned File:** `cleaned_mall_customers.csv`

---

## 🛠 Tools Used
- Jupyter Notebook (Anaconda)
- Python 3
- Pandas Library

---

## 🔍 Cleaning Steps Performed

1. **Loaded the dataset** using Pandas and previewed initial rows.
2. **Checked for missing values** using `.isnull().sum()` — none were found.
3. **Removed duplicates** using `.drop_duplicates()` — no duplicate rows existed.
4. **Standardized categorical text** in the `Genre` column (e.g., converted to lowercase, removed extra spaces).
5. **Renamed column headers** to be lowercase and use underscores (e.g., `Annual Income (k$)` → `annual_income_k$`).
6. **Validated and fixed data types** (ensured `Age` is integer, others appropriate).
7. **Exported** the cleaned dataset as `cleaned_mall_customers.csv`.

---

## 📁 Output Files

- ✅ `Mall_Customers.csv` – Raw dataset
- ✅ `cleaned_mall_customers.csv` – Cleaned and formatted dataset
- ✅ `data_cleaning_task1.ipynb` – Jupyter notebook with step-by-step code
- ✅ `screenshots/` – Folder containing visual proof of key steps (optional)
- ✅ `README.md` – This explanation file

---

## 📌 Summary
The dataset was cleaned successfully by:
- Ensuring consistency in column formats
- Handling potential data quality issues
- Preparing the dataset for future analysis or modeling tasks

---

## 🧠 Learning Outcomes
- Gained experience in real-world data preprocessing
- Practiced handling common data issues (nulls, duplicates, text formats)
- Strengthened Pandas skills in Jupyter Notebook

