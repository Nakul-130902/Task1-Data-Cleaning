# Task1-Data-Cleaning
"Internship Task‑1: Data Cleaning and Preprocessing (Netflix Dataset)"
# Task 1: Data Cleaning & Preprocessing

## 🎯 Objective
Clean and prepare raw Netflix dataset (titles.csv) by handling nulls, duplicates, and inconsistent formats.

## 🛠️ Tools
- Python (Pandas)
- Jupyter Notebook

## 📌 Steps Done
- Removed 1 missing title row
- Filled 18 missing descriptions with `"No description available"`
- Filled 2619 missing age_certification with `"Unknown"`
- Filled 3744 missing seasons with 0
- Filled IMDb/TMDB missing values with median
- Standardized text in `title`, `genres`, `production_countries`
- Saved cleaned dataset as `titles_cleaned.csv`

## 📂 Files in Repository
- `titles.csv` → Raw dataset
- `titles_cleaned.csv` → Cleaned dataset
- `task1_cleaning.ipynb` → Jupyter Notebook with full code
- `README.md` → This summary file

## ✅ Outcome
Created a clean and structured dataset ready for analysis and visualization.

