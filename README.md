# **Store Item Demand Forecasting Project**

## **Project Overview**

This project focuses on developing an XGBoost model to **forecast sales** for a retail dataset. The dataset comprises **5 years** of daily store-item sales data, covering **50 different items** across **10 store locations**. The main goal is to accurately predict the sales for each item over the next **3 months**.

## **Workflow**

### **1. Data Analysis**
- Check for seasonalities or patterns between sales of each item for each store

### **2. Data Preprocessing**
- Check for missing data.
- Feature engineering using 'year', 'month', 'day', 'day_of_week', 'day_of_year' and 'week_of_year'.
- Generated lag features
- Generated rolling mean features

### **2. Model Development**
- Trained and fine-tuned an XGBoost model.

### **3. Evaluation**
- Achieved a validation SMAPE or Symmetric Mean Absolute Percentage Error of **12.6206** (For reference, the top 1 in the Kaggle leaderboard is 12.5802)

### **4. Visualization**
- Plotted sales forecasts over the next 3 months for every item in each store
