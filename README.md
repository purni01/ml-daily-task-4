# ml-daily-task-4

# 🔍 Breast Cancer Prediction using Logistic Regression

This is Task 4 of my AI & ML Internship. In this task, I built a **binary classification model** using **Logistic Regression** on the Breast Cancer Wisconsin dataset. The goal was to predict whether a tumor is malignant or benign.

 What I Did

- Chose the Breast Cancer dataset from Kaggle
- Preprocessed the data and encoded the target labels
- Split the dataset into training and test sets
- Standardized the features for better model performance
- Trained a logistic regression model using Scikit-learn
- Evaluated the model using:
  - Confusion Matrix  
  - Precision, Recall, F1-score  
  - ROC Curve and AUC Score
- Explored how the sigmoid function works
- Tried different classification thresholds to understand their impact

 Tools & Libraries Used

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- NumPy

 Model Performance

- **Precision**: 0.97
- **Recall**: 0.99
- **F1-Score**: 0.98
- **ROC-AUC Score**: 0.99


 Threshold Tuning

I experimented with the classification threshold to see how it affects the confusion matrix. Lowering the threshold increased sensitivity but also increased false positives. This helped me understand the trade-off between **precision** and **recall**.



 What I Learned

- How logistic regression models probability using the **sigmoid function**
- How to interpret evaluation metrics like **precision, recall, F1-score**, and **ROC-AUC**
- Why threshold tuning matters in classification problems
- How to handle binary classification tasks end-to-end



