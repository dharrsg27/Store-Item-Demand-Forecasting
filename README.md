# **Retail Sales Forecasting Project**

## **Project Overview**

This project focuses on developing an XGBoost model to **forecast sales** for a retail dataset. The dataset comprises **5 years** of daily store-item sales data, covering **50 different items** across **10 store locations**. The main goal is to accurately predict the sales for each item over the next **3 months**.

## **Workflow**

### **1. Data Analysis**
- Check for seasonalities or patterns between sales of each item for each store

### **2. Data Preprocessing**
- Check for missing data.
- Feature engineering using 'year', 'month', 'day', 'day_of_week', 'day_of_year' and 'week_of_year'.
- Generating lag features to capture historical sales patterns.
- Creating rolling statistics for trend analysis.

### **2. Model Development**
- Trained and fine-tuned an XGBoost model.

### **3. Evaluation**
- - Achieved a training RMSE of **6.68** and a validation RMSE of **7.32**

### **4. Visualization**
- Plotted sales forecasts over the next 3 months for every item in each store
