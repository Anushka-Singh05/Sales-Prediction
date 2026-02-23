
# 📊 Sales Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting product sales based on advertising budgets across different channels — **TV, Radio, and Newspaper**.

The objective is to analyze the dataset, perform exploratory data analysis (EDA), train multiple machine learning models, compare their performance, and determine the best predictive model.

---

## 🎯 Objectives
- Perform data cleaning and visualization
- Understand relationships between advertising channels and sales
- Train regression models
- Evaluate model performance
- Compare Linear Regression and Random Forest
- Predict future sales

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were performed:

- 📦 Boxplot to detect outliers  
- 📈 Pairplot to analyze relationships between features  
- 📊 Distribution plots (distplot) to understand feature spread  
- 🔥 Correlation heatmap to identify strong relationships  
- ❗ Missing value heatmap  

### Key Observations:
- TV advertising shows strong correlation with Sales
- Minimal missing values
- Slight non-linearity observed in feature relationships

---

## 🧠 Models Used

### 1️⃣ Linear Regression

Based on the fundamental regression equation:


y = mx + b


Where:
- y = Predicted Sales
- x = Advertising Spend
- m = Coefficient
- b = Intercept

📊 Performance:
- MSE: **2.90**
- RMSE: **1.70**
- R² Score: **0.9059**

---

### 2️⃣ Random Forest Regressor 🌳

A tree-based ensemble model capable of capturing non-linear relationships.

📊 Performance:
- MSE: **1.42**
- RMSE: **1.19**
- R² Score: **0.9538**

---

## 📈 Model Comparison

| Model              | MSE   | RMSE  | R² Score |
|--------------------|-------|-------|----------|
| Linear Regression  | 2.90  | 1.70  | 0.9059   |
| Random Forest      | 1.42  | 1.19  | 0.9538   |

🔎 **Conclusion:**  
Random Forest outperformed Linear Regression with lower error and higher R² score, indicating that the relationship between advertising spend and sales contains non-linear patterns.

---

## ⚙️ Workflow

1. Import Dataset
2. Data Cleaning
3. EDA & Visualization
4. Feature Selection (`TV`, `Radio`, `Newspaper`)
5. Train-Test Split (80-20)
6. Model Training
7. Prediction (`y_pred`)
8. Model Evaluation

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Future Improvements
- Hyperparameter tuning (GridSearchCV)
- Feature importance visualization
- Residual analysis
- Model deployment using Flask/Streamlit

---

⭐ *"Transforming advertising data into predictive business insights."*
