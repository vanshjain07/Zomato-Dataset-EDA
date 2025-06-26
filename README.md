# 🍽️ Zomato Restaurant Dataset - Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on the Zomato restaurant dataset. The goal is to explore key features, identify missing values, and understand the structure of the data to prepare it for further analysis and modeling.

---

## 📂 Dataset Information

- **File:** `zomato.csv`
- **Additional File:** `Country-Code.xlsx`
- **Source:** Zomato (via Kaggle or public dataset portals)
- **Encoding:** Latin-1

---

## 📌 Objectives

- Inspect the structure and attributes of the dataset
- Handle missing values effectively
- Understand the distribution of numerical and categorical variables
- Load and join country codes for further geographic insights
- Prepare the data for visualization or ML models

---

## 🔍 Key EDA Steps

### ✅ 1. Importing Required Libraries
- `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`

### 📊 2. Dataset Overview
- Previewing dataset using `.head()`, `.info()`, and `.describe()`
- Checking column names and data types

### 🧹 3. Handling Missing Data
- Used `.isnull().sum()` to identify null values
- Extracted columns with missing data using list comprehension

### 🔗 4. Merging Country Data
- Loaded `Country-Code.xlsx` using `pd.read_excel()`
- Ready for merging with Zomato data using `Country Code` column

---

## 📁 Project Structure
├── zomato.csv

├── Country-Code.xlsx

├── EDA.ipynb

├── README.md


---

## 🧠 Insights (So Far)

- The dataset contains several missing values across multiple columns  
- Numeric and categorical columns are clearly distinguishable  
- Country data is external and useful for enriching the Zomato dataset  
- Data is ready for further cleaning, feature engineering, and visualization

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🙌 Acknowledgements

Thanks to Zomato and dataset contributors for making the data publicly available. This project is intended for learning and analytical practice.

---

## 📜 License

This project is for educational and research use only.


