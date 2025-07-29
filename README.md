# 📈 Market Regime Prediction using Machine Learning

This project focuses on **predicting market regimes** (Bull, Bear, Sideways) using **macroeconomic and financial indicators**.  
The study combines traditional **time-series models** (ARIMA, GARCH) with **machine learning classifiers** to capture both statistical properties and nonlinear patterns in financial data.

---

## 📂 Files in Repository
- `Market_Regime_Prediction.ipynb` → Jupyter Notebook containing preprocessing, feature engineering, model training, and evaluation.  
- `README.md` → Documentation of the project.  

---

## ⚙️ Libraries Used
The following Python libraries were used:
- **pandas** → Data manipulation  
- **numpy** → Numerical operations  
- **matplotlib**, **seaborn** → Visualization  
- **scikit-learn** → Machine learning (Logistic Regression, Random Forest, XGBoost, SVM)  
- **statsmodels** → ARIMA, GARCH models  
- **xgboost** → Gradient boosting model  

---

## 📝 Workflow
1. **Data Collection**  
   - Historical stock market and macroeconomic indicators (GDP growth, interest rate, inflation, volatility index, etc.)  

2. **Data Preprocessing**  
   - Handling missing values  
   - Normalization/standardization  
   - Feature selection (removing redundant variables)  

3. **Feature Engineering**  
   - Rolling averages, volatility, momentum indicators  
   - Lag features for time-series dependencies  

4. **Modeling**  
   - **Classification Models** → Logistic Regression, Random Forest, XGBoost, SVM  
   - **Time-Series Models** → ARIMA, GARCH for volatility forecasting  

5. **Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
   - Comparison between machine learning and statistical models  
