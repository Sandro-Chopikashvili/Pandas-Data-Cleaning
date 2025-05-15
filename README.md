# 🧹 Big DataFrame Cleaning with Pandas & NumPy

This project demonstrates a comprehensive data cleaning workflow using only **pandas** and **NumPy**. It simulates a large, messy dataset and walks through common data cleaning steps typically required in real-world data science and analytics tasks.

---

## 📦 What’s Inside

- `data_cleaning.py`: Main script that:
  - Generates a fake large dataset with common data issues
  - Cleans and transforms the data using pandas and NumPy
  - Handles missing values, outliers, incorrect types, string issues, and more
  - Creates new features and outputs a cleaned DataFrame

---

## 🔧 Key Cleaning Steps

### ✅ Basic Cleaning
- Remove duplicate rows
- Replace or drop missing values (`NaN`)
- Strip whitespace and unify case formatting

### 📅 Date Handling
- Convert string dates into proper `datetime` objects
- Drop or fix invalid date formats

### 🧪 Data Standardization
- Standardize categories (e.g., normalize country names like `us`, `USA`, `UsA`)
- Convert `Subscribed` column to clean boolean values

### 💥 Outlier Detection
- Remove outliers in `Income` using standard deviation thresholding

### ✨ Feature Engineering
- Extract `Signup Year` from dates
- Create new flags like `Is_USA`

### 🗂️ Reorganization
- Rename columns for clarity
- Reorder columns into logical structure

---

## 🧰 Requirements

This script uses:
- `pandas`
- `numpy`


