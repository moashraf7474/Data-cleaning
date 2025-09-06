# 🏡 Data Cleaning & Visualization – Real Estate Dataset  

This project is part of my Data Science portfolio. The goal was to take a raw dataset, clean it, handle missing values, explore its structure, and visualize insights using Python.  

---

## 📂 Dataset  
The dataset used in this project is available on Kaggle:  
🔗 [Data Cleaning Portfolio Project](https://www.kaggle.com/datasets/deepalisukhdeve/data-cleaning-portfolio-project)  

---

## ⚡ Project Workflow  

### 1. Data Exploration  
- Loaded dataset with **pandas**.  
- Inspected structure with `.head()`, `.info()`, and `.describe()`.  
- Checked missing values with `.isnull().sum()`.  
- Identified data types and columns that required cleaning.  

### 2. Data Cleaning  
- **Missing values**:  
  - Dropped columns with more than 50–60% missing data using `dropna()`.  
  - Imputed categorical values using `fillna()` with mode (most frequent value).  
- **Duplicates**: Removed duplicate rows for data consistency.  
- **Standardization**: Cleaned categorical fields (e.g., `PropertyAddress`, `SoldAsVacant`).  
- Saved the cleaned dataset into `processed/portfolio_project_clean.csv`.  

### 3. Data Visualization  
Created clear and insightful visualizations using **Matplotlib** and **Seaborn**:  
- **Histogram** → Distribution of Sale Prices.  
- **Boxplot** → Detect outliers in Sale Prices.  
- **Countplot** → Frequency of categorical variables (e.g., Land Use).  
- **Barplot** → Average Sale Price by property type.  
- **Heatmap** → Correlation between numerical features.  

Each visualization provided insights into the data and helped identify trends, outliers, and relationships.  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  

---

## 📊 Key Learnings  
- How to handle **missing data** using `dropna` vs `fillna`.  
- When to impute values vs when to drop them.  
- Using visualization to communicate findings effectively.  
- Building a reproducible workflow for data analysis.  

---

## 🚀 How to Run  
1. Clone this repository.  
2. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn
