# 📊 Real Estate Valuation – House Price Prediction

A machine learning project that predicts house prices using the Boston Housing dataset by implementing a complete data preprocessing and regression pipeline.

---

## 🚀 Project Overview

This project focuses on building a supervised machine learning model to estimate house prices based on housing and socioeconomic features.

The workflow includes:
- Data cleaning and preprocessing
- Outlier detection and treatment
- Model training using Linear Regression
- Performance evaluation and visualization

---

## 📂 Dataset

- **Dataset:** Boston Housing Dataset  
- **Rows:** 506  
- **Features:** 13  
- **Target:** MEDV (Median house price)

---

## ⚙️ Key Steps

### 🔹 Data Preparation
- Dataset exploration and statistical analysis
- Missing value analysis (no missing values found)
- Outlier detection using IQR and Z-score
- Outlier treatment using capping (Winsorization)

### 🔹 Model Development
- Train-test split (80/20)
- Linear Regression model training
- Feature importance analysis using coefficients

### 🔹 Model Evaluation
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Results

- **R² Score:** 0.752  
- **RMSE:** 3.484  
- Model shows strong predictive performance with no overfitting.

---

## 📊 Visualizations

### 🔹 Actual vs Predicted
![Actual vs Predicted](actual_vs_predicted.png)

### 🔹 Residual Plot
![Residual Plot](residual_plot.png)

### 🔹 Correlation Heatmap
![Heatmap](correlation_heatmap.png)

### 🔹 Outlier Detection (Boxplots)
![Boxplots](boxplots.png)

### 🔹 Model Performance
![Metrics](model_metrics.png)

---

## 🧠 Key Learning

Data preprocessing (especially handling outliers) plays a crucial role in improving model performance — not just the algorithm itself.

---

## 📌 Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔗 Repository

https://github.com/mubashir-azeem/BlackByte-Internship/tree/main/Project%20-%20Prediction%20of%20House%20Prices%20(Real%20Estate%20Valuation%20-%20Boston%20Dataset)

---

## 🙌 Feedback

Feel free to share feedback or suggestions!
