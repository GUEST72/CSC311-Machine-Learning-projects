# CSC311 - Assignment 1: Classification & Regression Fundamentals

**Course:** Introduction to Machine Learning (CSC311)  
**Instructor:** Dr. Marwan Torki, Eng. Youssef El-Ebiary 
---

## 🎯 Objectives
- Understand the concepts of **classification** and **regression**.
- Apply data preprocessing: balancing, splitting, and normalization.
- Implement ML models **from scratch** and using **Scikit-Learn**.
- Perform hyperparameter tuning and analyze overfitting/underfitting trends.
- Compare the performance of manual and library-based implementations.

---

## 📂 Project Structure

### **Part 1 — Classification (MAGIC Gamma Telescope dataset)**
- **Dataset Preparation:**
  - Balance dataset by downsampling the majority class.
  - Split into training (70%), validation (15%), and test (15%).
- **Implementation:**
  - K-NN classifier from scratch (distance calculation, nearest neighbors search, majority voting).
  - K-NN classifier using Scikit-Learn.
- **Analysis:**
  - Test multiple values of K.
  - Plot validation accuracy vs K for both methods.
  - Evaluate using accuracy, precision, recall, F1-score, and confusion matrix.
  - Discuss overfitting and underfitting.

---

### **Part 2 — Regression (California Housing dataset)**
- **Dataset Preparation:**
  - Split into training (70%), validation (15%), and test (15%).
- **Implementation:**
  - Linear Regression from scratch (Normal Equation & Gradient Descent).
  - Ridge (L2) and Lasso (L1) regression from scratch with regularization parameter tuning.
  - Repeat all models using Scikit-Learn.
- **Analysis:**
  - Plot validation error vs regularization parameter.
  - Compare manual vs library results.
  - Evaluate using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

---

## 🛠 Tools & Libraries
- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-Learn
