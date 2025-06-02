# 🌳 Decision Tree & Random Forest Classifier

## 🔍 Project Overview
This project explores and compares two tree-based classification algorithms:
- **Decision Tree**
- **Random Forest**

We use the **Heart Disease Dataset** to predict whether a patient has heart disease based on medical attributes.

---

## 📊 Dataset
**Source**: [Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
**Target Variable**: `target` (1 = disease, 0 = no disease)

---

## 🧰 Tools & Libraries
- Python (Jupyter Notebook)
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 🚀 Steps Performed
1. **Data Loading and Cleaning**
2. **Training a Decision Tree Classifier**
3. **Analyzing Overfitting with Depth Control**
4. **Training and Evaluating a Random Forest**
5. **Feature Importance Analysis**
6. **Cross-Validation for Model Robustness**
7. **Tree Visualization using `plot_tree()`**

---

## 📈 Results
| Model            | Test Accuracy | CV Accuracy |
|------------------|---------------|--------------|
| Decision Tree    | ~0.80         | ~0.78        |
| Random Forest    | ~0.87         | ~0.84        |

✅ Random Forest outperformed the single decision tree due to better generalization via ensemble learning.

---

## 📌 Key Concepts Covered
- Entropy and Information Gain
- Overfitting and Tree Pruning
- Ensemble Learning & Bagging
- Feature Importance Interpretation
- Cross-Validation Best Practices

---

## 📝 Author
Task completed as part of the **AI & ML Internship Program**.

