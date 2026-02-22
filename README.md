#  Retail Sales Forecasting Using Machine Learning

##  Project Overview
This project focuses on predicting weekly retail sales using Machine Learning techniques.  
The objective is to analyze how different factors such as store details, holidays, economic indicators, and promotions impact sales performance.

This project was completed as a First-Year BSc Data Science student to build strong fundamentals in Time Series Analysis and Machine Learning.

---

## Dataset Description
The dataset consists of:

- train.csv – Historical weekly sales data  
- features.csv – Economic indicators and promotional markdown data  
- stores.csv – Store type and size information  

The datasets were merged using common columns such as *Store* and *Date*.

---

## Project Workflow
1. Data Loading using Pandas  
2. Data Cleaning and handling missing values  
3. Feature Engineering (Year, Month, Week extraction)  
4. Merging multiple datasets  
5. Train-Test Split  
6. Model Training  
7. Model Evaluation using MAE  

---

##  Machine Learning Models Used
- Linear Regression  
- Random Forest Regressor  

Random Forest performed better for this dataset.

---

##  Model Performance
Optimized Mean Absolute Error (MAE): *1565.26*

This means the model’s predictions were on average off by approximately 1565 sales units.

---

## Feature Importance Insights
Most important features affecting sales:

- Department  
- Store  
- CPI  
- Week  
- Unemployment  

Holiday impact was comparatively low.

---

##  Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  
- Anaconda  

---

##  Key Learning Outcomes
- Real-world data preprocessing  
- Debugging merge and model errors  
- Understanding evaluation metrics  
- Feature importance interpretation  
- Model optimization  

---

⭐ If you found this project interesting, feel free to star the repository!
