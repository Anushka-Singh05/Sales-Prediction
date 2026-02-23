# 📊 Sales Prediction using Machine Learning

## 📌 Project Overview
This project predicts product sales based on advertising budgets (TV, Radio, Newspaper).  
Both **Linear Regression** and **Random Forest Regressor** models were implemented and compared.

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were used:

- Boxplot to detect outliers  
- Pairplot to observe relationships between features  
- Distribution plots for feature spread  
- Heatmap for correlation analysis  
- Missing value heatmap  

Libraries used:
- Matplotlib
- Seaborn

---

## 🧠 Models Used

### 1️⃣ Linear Regression

Based on:

y = mx + b

- MSE: **2.90**
- RMSE: **1.70**
- R² Score: **0.9059**

---

### 2️⃣ Random Forest Regressor 🌳

- MSE: **1.42**
- RMSE: **1.19**
- R² Score: **0.9538**

---

## 📈 Model Comparison

| Model              | MSE   | RMSE  | R² Score |
|--------------------|-------|-------|----------|
| Linear Regression  | 2.90  | 1.70  | 0.9059   |
| Random Forest      | 1.42  | 1.19  | 0.9538   |

🔎 **Observation:**  
Random Forest performed better with lower error and higher R² score.

---

## ⚙️ Workflow

1. Data Cleaning
2. Correlation Analysis
3. Feature Selection (TV, Radio, Newspaper)
4. Train-Test Split (80-20)
5. Model Training
6. Prediction (`y_pred`)
7. Evaluation

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

## 🚀 Conclusion
Random Forest outperformed Linear Regression, indicating that the relationship between advertising channels and sales may be slightly non-linear.

---

⭐ *"From raw data to predictive insight."*

Now listen carefully Anu 👀🔥

Your R² = 0.9538 for Random Forest is actually VERY GOOD.
This is internship-ready level project.

If you want next level upgrade, we can:

Add feature importance graph

Add residual plot

Add hyperparameter tuning (GridSearchCV)

Or write LinkedIn post for this project

Tell me… portfolio polish karein ya next project shuru karein? 😌

see jo tune upar read me file di thi isse pehle uska bhi chahiye content in this merge boty the files


Achaaa samajh gayi 😌🔥
Tum chahti ho pehle wala structured README + naya detailed model comparison wala README dono merge karke ek strong final version mile.

Okay madam, this will be your final polished combined Sales Prediction README 👇

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
