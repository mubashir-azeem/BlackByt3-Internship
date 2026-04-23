# 📊 Retail Sales Forecasting using Time-Series (Walmart Dataset)

## 📌 Project Overview
This project focuses on forecasting Walmart retail sales using time-series analysis. The goal is to analyze historical weekly sales data, identify patterns such as trends and seasonality, and predict future sales to support better inventory and demand planning.

---

## 🎯 Objective
- Understand sales behavior over time  
- Identify seasonal trends and peak demand periods  
- Forecast future sales using ARIMA model  
- Provide business insights for inventory optimization  

---

## 📂 Dataset
The dataset contains weekly sales data for Walmart stores.

### Key Features:
- **Date** – Time variable  
- **Weekly_Sales** – Target variable  
- **Store** – Store ID  
- **Holiday_Flag** – Indicates holiday weeks  
- Additional features: Temperature, Fuel Price, CPI, Unemployment  

---

## ⚙️ Data Preprocessing
- Converted Date column to datetime format  
- Extracted Year, Month, Week, and Day features  
- Sorted data and set Date as index  
- Checked for missing values and duplicates  
- Selected Store 1 for time-series forecasting  

---

## 📊 Exploratory Data Analysis
- Visualized weekly sales trends  
- Identified seasonal patterns  
- Analyzed holiday vs non-holiday sales  
- Observed peak demand during late-year months  

---

## 🤖 Model Used
### ARIMA (1,1,1)
- Checked stationarity using ADF test  
- Applied differencing for stability  
- Trained ARIMA model on weekly sales  
- Forecasted next 8 weeks  

---

## 📈 Results & Evaluation
- **MAE:** ~82,653  
- **RMSE:** ~89,645  

The model shows stable performance with no extreme errors and captures overall sales patterns effectively.

---

## 📊 Visualizations

### Sales Trend
![Sales Trend](images/sales_trend.png)

### Monthly Sales
![Monthly Sales](images/monthly_sales.png)

### Forecast
![Forecast](images/forecast.png)

### Actual vs Predicted
![Comparison](images/actual_vs_predicted.png)

---

## 💼 Business Insights
- Sales peak during **November–December (holiday season)**  
- Demand drops in early months (Feb–March)  
- Clear seasonality observed in sales patterns  
- Forecasting helps optimize inventory and avoid stockouts  

---

## 📌 Final Conclusion
Based on the forecasting results, sales are expected to increase during November and December. Inventory should be increased during these periods to avoid stockouts. Off-season demand drops during early-year months such as February and March, suggesting optimized storage management.

---

## 📁 Repository Contents
- Jupyter Notebook (complete project)
- Walmart dataset
- Final PDF report
- Visualizations (graphs)
- Forecasting model implementation

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  
- Scikit-learn  

---

## 🚀 Future Improvements
- Implement SARIMA for seasonal modeling  
- Compare ARIMA with regression models  
- Perform time-series cross-validation  

---

## 📎 Author
**Mubashir Azeem Abbasi**
