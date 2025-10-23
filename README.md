# 🩺 Multiclass Diabetes Classification
This project aims to classify diabetes into multiple categories using a dataset from [Kaggle](https://www.kaggle.com/datasets/yasserhessein/multiclass-diabetes-dataset).  
Machine learning algorithms are applied to analyze patient data and predict the level or type of diabetes based on several medical attributes.

---

## Open in Google Colab
Click the badge below to run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/malonasntr/machine-learning-diabetes/blob/0d5bcbd4fc725d1fa9c9d6b248e9586f20d8e87f/machine_learning.ipynb)

---

## Dataset
**Source:** [Multiclass Diabetes Dataset – Kaggle](https://www.kaggle.com/datasets/yasserhessein/multiclass-diabetes-dataset)

The dataset includes multiple attributes such as:
- Age  
- Gender  
- Polyuria  
- Polydipsia  
- Sudden weight loss  
- Weakness  
- Partial paresis  
- Class (diabetes type)

---

## Machine Learning Workflow
1. **Data Preprocessing**
   - Handle missing values  
   - Encode categorical variables  
   - Normalize/scale numerical features  

2. **Model Training**
   - Logistic Regression  
   - Random Forest  
   - Support Vector Machine (SVM)  
   - XGBoost  

3. **Model Evaluation**
   - Confusion Matrix  
   - Accuracy, Precision, Recall, F1-Score  
   - Visualization of results  

---

## Results Summary
| Model | Accuracy | Notes |
|--------|-----------|--------|
| Logistic Regression | — | Baseline model |
| Random Forest | — | Best performance on recall |
| SVM | — | Moderate accuracy |
| XGBoost | — | Best overall accuracy |

*(Fill in the performance metrics after training.)*

---

## 🧩 Requirements
If you want to run this project locally:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
