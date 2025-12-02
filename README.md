# Breast Cancer Classification using Logistic Regression & Multicollinearity Analysis

### Overview  
This project is an introductory machine learning analysis focused on predicting breast cancer diagnosis using clinical features. It demonstrates a complete ML workflow — from exploratory analysis to model evaluation — while diving deeper into an important statistical concept: **multicollinearity**.

This project helped build foundational skills that I apply in more advanced, domain-specific analytics projects.



 Objectives  
- Explore the Breast Cancer dataset  
- Understand relationships between features  
- Detect and evaluate **multicollinearity**  
- Apply **Logistic Regression** for binary classification  
- Evaluate model performance using standard metrics  



 Dataset  
Dataset: Breast Cancer Wisconsin Diagnostic Dataset  
Source: Scikit-learn / UCI Machine Learning Repository  
Target variable:  
- `diagnosis` — **M = Malignant** / **B = Benign**



### Steps Performed  
 Data loading and cleaning  
Feature correlation and visualization  
 Multicollinearity check
 Feature selection and reduction  
 Logistic Regression Model training  
 Performance evaluation and interpretation  



Metrics used:

- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  
- ROC–AUC Curve  

These measures help assess not just correctness but also the model’s *ability to detect malignant cases*, which is clinically important.



Key Learning & Insights  
- Highly correlated features can **distort model interpretability**
- Removing multicollinear features improves model stability  
- Logistic regression can be a strong baseline for diagnostic prediction  
- Domain context matters: minimizing false negatives is crucial in healthcare  




 



