# 📱 Smartphone Data Cleaning using Pandas

## 🔍 Objective
Clean and transform a raw smartphone dataset using Python (Pandas) by handling inconsistencies, missing values, and unstructured columns to make it analysis-ready.

---

## 🛠️ Tools Used
- Python  
- Pandas  
- NumPy  

---

## ⚙️ Approach

### 🧠 Data Understanding
- Identified multiple data quality issues:
  - Inconsistent brand naming  
  - Incorrect values in columns (e.g., battery info in processor column)  
  - Missing values in rating, OS, and other fields  
  - Incorrect price formatting (₹ symbol, commas)  

---

### 🧹 Data Cleaning
- Removed unwanted symbols and converted price to numeric  
- Handled null values across multiple columns  
- Removed outliers (e.g., invalid price entries)  
- Ensured correct data types  

---

### 🔄 Data Transformation
- Standardized categorical values (OS, brand names)  
- Cleaned and structured text-based columns  

---

### 🧩 Feature Engineering
- Split complex columns into meaningful features:
  - Processor → brand, speed, cores  
  - RAM → RAM & storage  
  - Battery → capacity & charging  
  - Display → size, resolution, refresh rate  
  - Camera → rear/front camera details  
  - SIM → 5G, NFC, IR support  

---

## 📈 Key Outcomes
- Converted messy dataset into structured format  
- Improved data consistency and usability  
- Created multiple analytical features for deeper insights  

---

## 📂 Files Included
- Jupyter Notebook (.ipynb)  
- Dataset  

---

## 💡 Note
This project demonstrates strong data cleaning, preprocessing, and feature engineering skills using Pandas.
