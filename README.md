# Outlier Detection Using Statistical and Machine Learning Methods

This project focuses on detecting outliers in the **CreditCard.csv** dataset using a combination of **statistical techniques** and **machine learning algorithms**. Outlier detection is crucial in financial datasets, especially for identifying potentially fraudulent transactions or irregular behavior. The project includes data preprocessing, multiple outlier detection methods, visualization, and comparison of results.

---

##  **Project Overview**

The goal of this project is to:
- Understand the distribution of credit card transactional data  
- Apply various statistical and machine learning outlier detection methods  
- Visualize anomalies to identify patterns  
- Compare the effectiveness of traditional vs ML-based techniques  

This project includes the following outlier detection methods:
- **Tukey’s IQR Method**
- **Standard Deviation Method**
- **Z-Score Method**
- **Modified Z-Score Method**
- **Isolation Forest Algorithm**

---

##  **Dataset**

The dataset used in this project is:

**`CreditCard.csv`**

This dataset typically contains:
- Transaction amount  
- Time of transaction  
- PCA-transformed features (V1–V28)  
- `Class` (0 = Normal, 1 = Fraud)

---

## **Outlier Detection Methods**

### ✔️ **1. Tukey’s IQR Method**
Detects outliers based on the interquartile range:
- Outlier if value < Q1 – 1.5 × IQR  
- Outlier if value > Q3 + 1.5 × IQR  

### ✔️ **2. Standard Deviation Method**
Values beyond **mean ± 3×STD** are flagged.

### ✔️ **3. Z-Score Method**
Outliers are data points with:
- Z-score > 3 or < -3  

### ✔️ **4. Modified Z-Score Method**
More robust for skewed data:
- Uses median and MAD  
- Outlier if Modified Z > 3.5  

### ✔️ **5. Isolation Forest**
A machine learning model that isolates anomalous points via random tree splits.

---

## **Visualizations**

The project includes:
- Boxplots  
- Distribution plots  
- Scatterplots highlighting anomalies  

Visualizing outliers helps understand where anomalies occur and how different methods behave.

---
