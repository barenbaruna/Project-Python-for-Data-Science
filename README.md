## IBM HR Attrition Analysis - 98% Model Accuracy

### Author: MARYAM NOROOZI
### [Link to Kaggle Code](https://www.kaggle.com/code/maryamnoroozi68/ibm-hr-attrition-analysis-98-model-accuracy)
### [Link to Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)
---

### 📝 Project Description:

In a work environment, Employee Attrition describes an unanticipated attrition of the workforce. The causes of this decline are all unavoidable reasons such as retirement, resignation, loss of work capacity, or sudden death. Companies with high workforce attrition rates often face the risk of abusing internal resources.

**Purpose:**

- Discover the factors that affect employee attrition and then take measures to reduce this rate.
- Build a machine learning model based on employee factors to predict whether that employee is likely to attrition or not?

---

### 📊 Data Discovery:

- The dataset contains 1470 rows and 35 columns, with features like age, gender, education, job role, satisfaction levels, etc.
- There are no missing values or duplicate rows in the dataset.
- Some columns such as 'Over18', 'EmployeeNumber', 'EmployeeCount', 'StandardHours' have been removed as they do not affect the analysis results.

---

### 📈 Discovering Relationships in Data:

- Explored relationships between various features and attrition using visualizations like count plots, pie charts, and box plots.
- Identified patterns such as higher attrition among younger employees, those who travel frequently, and those with lower job satisfaction.
- Analyzed relationships between features like age, income, gender, and attrition.

---

### 🤖 Machine Learning Models:

**1. Logistic Regression:**
- Achieved an accuracy of `76%`.
- Confusion matrix revealed `38`, `188`, `11`, `57`.
- Precision, Recall, and F1-score were calculated.

**2. Random Forest:**
- Achieved an accuracy of `98%`.
- Confusion matrix depicted the model's performance.
- Precision, Recall, and F1-score were analyzed.

**3. Gradient Boosted:**
- Achieved the highest accuracy of `98%`.
- Confusion matrix showed the model's effectiveness.
- Precision, Recall, and F1-score were evaluated.

---

### 🔍 Summary:

- Conducted a thorough analysis of IBM HR attrition dataset.
- Employed SMOTE technique to handle imbalanced data distribution.
- Built and evaluated machine learning models to predict employee attrition, with the Gradient Boosted model achieving the highest accuracy of 98%.

--- 

### Conclusion:

This project provides valuable insights into the factors influencing employee attrition and offers a reliable model for predicting attrition, enabling organizations to take proactive measures to mitigate workforce loss.
