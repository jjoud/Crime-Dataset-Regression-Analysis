# Crime-Dataset-Regression-Analysis
# 📊 Crime Dataset Regression Analysis

## 🔹 Project Goal
Analyze community crime data in the United States and build regression models to predict violent crime rates per 100,000 population, while identifying the most influential demographic and social factors.

## 🔹 Dataset
- **Source:** [UCI Machine Learning Repository – Communities and Crime](https://archive.ics.uci.edu/dataset/183/communities+and+crime)  
- **Description:** 1,994 U.S. communities, 128 attributes (demographic, economic, housing, law enforcement).  
- **Target Variable:** `ViolentCrimesPerPop`.

## 🔹 Data Preparation
- Handled missing values (removed attributes with large gaps such as police data).  
- Dropped non-numeric or irrelevant features (e.g., community names).  
- Normalization not required since most attributes are already scaled between 0 and 1.  
- Correlation analysis performed to reduce redundancy and improve performance.

## 🔹 Models Applied
- **Linear Regression:** Captures direct relationships.  
- **Ridge Regression:** Adds stability through L2 regularization.  
- **Random Forest Regressor:** Captures non-linear relationships using 100 decision trees.

## 🔹 Evaluation Metrics
- Metrics used: **MAE, MSE, R²**.  
- Results:  
  - Linear Regression → R² = 0.6383  
  - Random Forest → R² = 0.6127  
  - Ridge Regression → R² = 0.6450  

## 🔹 Key Findings
- All models achieved comparable performance.  
- **Ridge Regression** provided the best balance between accuracy and stability.  
- Data preprocessing significantly improved model reliability.

## 🔹 Conclusion
This project demonstrates how regression models can predict violent crime rates using real-world community data. Careful data preparation and model selection are essential for building reliable predictive systems in social science applications.



