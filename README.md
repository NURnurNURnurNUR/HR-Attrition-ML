# HR Attrition ML - Predicting Employee Attrition

A machine learning-based employee attrition predictor using **Logistic Regression** and **SVM (RBF Kernel)**. The tool compares both models using performance metrics to determine the best fit for this classification task.

## Dataset Link

### [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)

## Features

* **Data Preprocessing**: Encoding categorical variables, handling class imbalance, feature scaling
* **Attrition Prediction**: Classifies whether an employee is likely to **stay** or **leave**
* **Model Comparison**


## Installation & Setup

### 1. **Clone the Repository**

```bash
git clone https://github.com/YOUR_USERNAME/HR-Attrition-ML.git
cd HR-Attrition-ML
```

### 2. **Install Dependencies**

```bash
pandas
numpy
matplotlib
imbalanced-learn
scikit-learn
```


## Summary of Results

| Model               | Training Accuracy | Testing Accuracy |
| ------------------- | ----------------- | ---------------- |
| Logistic Regression | **89.5%**         | **90.5%**        |
| SVM (RBF Kernel)    | 83.2%             | 88.8%            |

> **Conclusion**: While both models perform well, **Logistic Regression** demonstrates **slightly better generalization** and **higher testing accuracy** on the HR attrition dataset. It is also **computationally less expensive**, making it a more efficient choice for this binary classification problem.



