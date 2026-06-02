# HR Promotion Prediction 👔

Predicting whether an employee will be **promoted** based on performance, demographics, and role features — using 10+ classification models with extensive hyperparameter tuning.

---

## Problem Statement
HR teams spend significant time manually reviewing promotion candidates. This project builds an ML pipeline to predict promotion likelihood, helping organisations prioritise high-potential employees objectively.

---

## Results

| Metric | Score |
|--------|-------|
| Best Model | Meta Estimator (Ensemble) |
| Accuracy | 92.17% |
| Precision | 0.59 |
| Recall | 0.41 |
| F1-Score | 0.48 |
| AUC-ROC | 0.69 |

> Meta Estimator selected for combining the strengths of multiple base classifiers — achieving the highest accuracy in a heavily imbalanced dataset.

---

## Models Compared
- Decision Tree & Tuned Decision Tree
- Logistic Regression & Tuned Logistic Regression
- K-Nearest Neighbours
- Naive Bayes
- Random Forest & Tuned Random Forest
- Extra Trees Classifier & Tuned Extra Trees
- AdaBoost
- XGBoost
- Meta Estimator ✅ *(best performer)*

---

## Visuals Included
- 📊 Correlation heatmap
- 📈 EDA plots (feature distributions, class imbalance analysis)
- 📉 Feature importance chart

---

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## Dataset
- **Task:** Binary classification (promoted / not promoted)
- **Challenge:** Class imbalance — majority of employees not promoted

---

## Project Structure

HR-Promotion-Prediction/
│
├── HR Promotion Model.ipynb   # Full notebook with EDA, modelling, evaluation
└── README.md

---

## Key Learning
Working with imbalanced datasets requires careful metric selection — accuracy alone is misleading when one class dominates. AUC-ROC and precision-recall trade-offs were the primary evaluation criteria here.
