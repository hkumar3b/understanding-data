# 📊 Understanding the Data

As part of the initial phase of this project, I performed a detailed data understanding step to explore the structure, quality, and relationships within the dataset. Below are the key aspects analyzed:

## 1. How big is the data?
- The dataset contains **891 rows** and **12 columns**.

## 2. How does the data look like?
- Displayed the first few rows to understand the format and types of data present in each column.

## 3. What is the data type of each column?
- Identified the data types: `int64`, `float64` for numerical columns, and `object` for categorical/text columns.

## 4. Are there any missing values?
- Noted missing values in:
  - `Age`: 177 missing
  - `Cabin`: 687 missing
  - `Embarked`: 2 missing

## 5. How does the data look mathematically?
- Used descriptive statistics to analyze distribution, central tendency, and spread of numeric features like `Age`, `Fare`, `SibSp`, etc.

## 6. Are there duplicate values?
- Checked for duplicates and confirmed **no duplicate rows** were found in the dataset.

## 7. How is the correlation between columns?
- Created a correlation matrix to study the relationship between numerical features.
  - Notable: Negative correlation between `Pclass` and `Fare`, positive correlation between `SibSp` and `Parch`.

---

This EDA helped identify important features, data quality issues, and relationships to guide further preprocessing and modeling.
