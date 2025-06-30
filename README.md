# BhoomiJaiswal0-PRODIGY_DS_03
# 🌳 Task 03 - Decision Tree Classifier | Prodigy InfoTech Internship

Build a decision tree classifier to predict whether a customer will purchase a product or service based on their **demographic** and **behavioral** data.

---

## 🔍 Problem Statement

Use a dataset such as the [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) from the UCI Machine Learning Repository to:
- Analyze customer data
- Train a Decision Tree model
- Predict whether a customer will subscribe to a term deposit

---

## 📁 Dataset Details

- **Source**: UCI Machine Learning Repository
- **Dataset**: `bank-full.csv`
- **Target Variable**: `y` (binary: "yes" or "no")

---

## 🧠 Technologies Used

- Python
- Pandas
- scikit-learn
- Matplotlib

---

## ⚙️ Steps Followed

1. **Load and Explore Data**
   - View dataset structure and target class distribution

2. **Data Preprocessing**
   - Label Encoding for target variable
   - One-Hot Encoding for categorical features

3. **Train-Test Split**
   - 80% training, 20% testing

4. **Model Training**
   - Used `DecisionTreeClassifier` from scikit-learn

5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

6. **Visualization**
   - Decision Tree (top levels)
   - Feature Importance (Top 10 features)

---

## 📈 Results

- Achieved accuracy: **~87%**
- Model interprets well and is useful for understanding customer decision patterns
- Easily extendable to improve recall using advanced models or class balancing

---

## 📊 Visuals

> Include decision tree plot and feature importance plot here (optional for GitHub)

---

## 📌 Conclusion

This task demonstrates how Decision Trees can be applied in real-world business problems like customer targeting. The results are interpretable and show promising accuracy, laying the foundation for future improvement using ensemble methods.

---

## ✅ Internship Credit

This project is submitted as part of **Task 3** under the **Prodigy InfoTech Data Science Internship Program**.

---
