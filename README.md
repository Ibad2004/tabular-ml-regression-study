# 📊 Regression Model Comparison

A research-oriented machine learning project focused on analyzing regression models on tabular data using a structured experimental pipeline.

---

## 📄 Research Paper

This project includes a research-style paper based on systematic experimentation and analysis.

📥 **Download Paper:** [paper/paper.pdf](paper/paper.pdf)

### 📊 Paper Highlights

- Comparative analysis of multiple regression models  
- Impact of preprocessing and feature engineering  
- Feature selection and dimensionality reduction  
- Evaluation of hyperparameter tuning  
- Insights into model performance on tabular data  

---

## 🎯 Objective

The goal of this project is to systematically compare multiple regression models and analyze how different machine learning techniques affect performance.

This project focuses on:

- Identifying the best-performing regression model  
- Analyzing the impact of preprocessing and feature engineering  
- Evaluating improvements from hyperparameter tuning  
- Following a research-oriented and reproducible ML workflow  

The emphasis is on **structured experimentation, model comparison, and analytical insights**.

---

## 🧠 Research Approach

This project follows a structured experimental workflow:


Modify → Train → Evaluate → Analyze → Document


This approach ensures:
- Reproducibility  
- Clear performance tracking  
- Deeper understanding of model behavior  

---

## ⚙️ Methodology

### 1️⃣ Data Cleaning & Preprocessing

- Handling missing values  
- Encoding categorical variables  
- Scaling numerical features  
- Train-test splitting  

---

### 2️⃣ Baseline Model Training

Models used:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor  

---

### 3️⃣ Model Evaluation

Evaluation metrics:

- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**  

---

### 📊 Visual Analysis

- Model comparison charts  
- Feature importance plots  
- Residual analysis  

---

### 4️⃣ Feature Engineering

Created features:

- HouseAge  
- RemodelAge  
- TotalBathrooms  
- TotalSF  
- TotalPorchSF  
- GarageAge  
- TotalLivingArea  

---

### 5️⃣ Encoding & Feature Selection

Encoding strategy:

- Binary → Label Encoding  
- Ordinal → Ordered Mapping  
- Nominal → One-Hot Encoding  

Feature selection:
- Based on Random Forest importance  
- Reduced features: **253 → 50**

---

### 6️⃣ Hyperparameter Tuning

- Method: **RandomizedSearchCV**
- Models tuned:
  - Random Forest  
  - Gradient Boosting  

---

## 📂 Dataset

- **Dataset:** House Prices (Kaggle)  
- **Samples:** 1460  
- **Target Variable:** SalePrice  

---

## 📁 Repository Structure


Regression-Comparison/

data/ # Dataset
notebooks/ # Experiment notebooks (01–06)
models/ # Saved models
paper/ # Research paper (PDF + LaTeX)
README.md


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

## 📈 Results Summary

| Stage | R² Score |
|------|--------|
| Baseline | ~0.89 |
| Preprocessing | ~0.90 |
| Feature Engineering | ~0.911 |
| Feature Selection | ~0.905 |
| Final Model | ~0.904 |

---

## 🔥 Key Insights

- Feature engineering had the **largest impact on performance**  
- Ensemble models (Gradient Boosting) performed best  
- Feature selection reduced dimensionality with minimal loss  
- Hyperparameter tuning provided **limited improvement**  

---

## 📌 Conclusion

This project demonstrates a complete machine learning pipeline from baseline models to an optimized solution.

Key takeaways:

- Data representation is more important than model complexity  
- Structured experimentation leads to better understanding  
- Ensemble models are highly effective for tabular datasets  

---

## 🚀 Future Work

- Classification model comparison  
- Deep learning approaches  
- Graph Neural Networks (GNNs)  
- Advanced optimization techniques  

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

## ⭐ About This Project

This project is part of a structured roadmap toward research-level machine learning, preparing for advanced topics such as:

- Deep Learning  
- Graph Neural Networks  
- Optimization techniques  

---