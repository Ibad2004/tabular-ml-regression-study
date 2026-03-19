# 📊 Regression Model Comparison

## 🎯 Objective

The goal of this project is to systematically compare multiple regression models on tabular data and analyze how different machine learning techniques affect performance.

This project focuses on:

- Identifying the best-performing regression model  
- Analyzing the impact of preprocessing and feature engineering  
- Evaluating improvements from hyperparameter tuning  
- Following a research-oriented and reproducible ML workflow  

The emphasis is on **structured experimentation, model comparison, and analytical insights**.

---

## ⚙️ Methodology

The project follows an **iterative experimental workflow**, similar to real-world machine learning research.

---

### 1️⃣ Data Cleaning & Preprocessing

Initial preprocessing includes:

- Handling missing values  
- Encoding categorical variables  
- Scaling numerical features  
- Train-test splitting  

---

### 2️⃣ Baseline Model Training

Baseline models are trained to establish initial performance benchmarks.

Models used:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  

---

### 3️⃣ Model Evaluation

Models are evaluated using standard regression metrics:

- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**  

---

### 📊 Visual Analysis

The following visualizations are used:

- Model comparison bar charts  
- Feature importance plots (tree-based models)  
- Residual plots (optional)  

All observations and results are documented inside notebooks.

---

### 4️⃣ Feature Engineering

New features were created using domain knowledge:

- HouseAge  
- RemodelAge  
- TotalBathrooms  
- TotalSF  
- TotalPorchSF  
- GarageAge  
- TotalLivingArea  

These features improved the model’s ability to capture real-world relationships.

---

### 5️⃣ Encoding & Feature Selection

A mixed encoding strategy was applied:

- Binary → Label Encoding  
- Ordinal → Ordered Mapping  
- Nominal → One-Hot Encoding  

Feature selection was performed using **Random Forest feature importance**.

Feature space reduction:


253 → 50 features


---

### 6️⃣ Hyperparameter Tuning

Hyperparameter tuning was performed using **RandomizedSearchCV** with cross-validation.

Models tuned:

- Random Forest Regressor  
- Gradient Boosting Regressor  

---

### 7️⃣ Iterative Experimentation

Each experiment follows a research cycle:


Modify → Train → Evaluate → Analyze → Document


This allows systematic understanding of performance improvements.

---

## 📂 Dataset

- **Dataset:** House Prices (Kaggle)  
- **Samples:** 1460  
- **Target Variable:** SalePrice  

Dataset stored in:


data/


---

## 📁 Repository Structure


Regression-Comparison/

data/ # Dataset
notebooks/ # Experiment notebooks (01–06)
models/ # Saved models (final_model, scaler, features)
README.md # Project documentation


---

## 🧪 Experiments Overview

| Notebook | Description |
|--------|------------|
| 00 | GPU check |
| 01 | Baseline models |
| 02 | Preprocessing improvements |
| 03 | Feature engineering |
| 04 | Encoding + feature selection |
| 05 | Model tuning |
| 06 | Final model pipeline |

---

## 📈 Final Results

- **Best Model:** Gradient Boosting Regressor  
- **R² Score:** ~0.904 – 0.905  
- **RMSE:** ~27000  

---

## 🔥 Key Insights

- Feature engineering had the **largest impact on performance**  
- Tree-based ensemble models perform best on tabular data  
- Feature selection reduces dimensionality with minimal performance loss  
- Hyperparameter tuning provides **limited improvement**  

---

## 📌 Conclusion

This project demonstrates a complete machine learning pipeline, progressing from baseline models to a fully optimized solution.

Key takeaways:

- Data representation is more important than model complexity  
- Structured experimentation leads to better understanding  
- Ensemble models are highly effective for tabular datasets  

---

## 🚀 Future Work

- Classification model comparison  
- Deep learning approaches  
- Advanced feature engineering  
- Research-oriented model optimization  

---

## 🛠 Tools & Technologies

- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- VS Code  

---