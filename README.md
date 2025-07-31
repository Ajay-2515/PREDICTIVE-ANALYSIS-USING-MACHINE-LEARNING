# 💡 Predictive Analysis of Health Insurance Charges Using Machine Learning

This project predicts the **cost of insurance** for individuals based on demographics and health conditions using regression models. The aim is to identify the **factors impacting charges** and develop models that accurately predict medical costs.

---

## 🔍 Problem Statement

Insurance companies want to **predict customer charges** based on:
- Age, Sex, BMI, Smoking Status
- Region, Number of Children

This project builds ML models to understand feature impact and forecast charges.

---

## 📊 Dataset

- **Source**: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Rows**: 1,300+
- **Target Variable**: `charges`

---

## 🛠️ Tools & Libraries

- Python, Pandas, NumPy  
- Seaborn, Matplotlib for data visualization  
- Scikit-learn for model training  
- Models: Linear Regression, Random Forest, XGBoost  
- Feature Selection: Correlation, Mutual Info

---

## 🔁 Workflow

1. **Data Exploration** – Summary stats, missing values, boxplots  
2. **EDA** – Visualize influence of smoking, BMI, region  
3. **Feature Engineering** – Encode categorical, bin BMI  
4. **Feature Selection** – Correlation, mutual_info_regression  
5. **Model Training** – Train/test split + regression models  
6. **Evaluation** – R² Score, MAE, RMSE  

---

## 📈 Results

- XGBoost performed best with **R² ~ 0.92**  
- **Smoking** and **BMI** are major cost drivers  
- Region has minimal impact, Age has linear effect

---

## 📌 Future Improvements

- Add SHAP for interpretability  
- Hyperparameter tuning (GridSearchCV)  
- Deploy via Streamlit or FastAPI

---

## 📁 File Structure

