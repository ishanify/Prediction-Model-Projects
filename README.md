# Predictive Analytics
### What this repository contains??
I have created many prediction models in Python and R on different data sets such as Credit Card Application Approval, Prostate Cancer, Wine Quality and more. Each project would be better than the previous one as I learn to apply more advanced concepts of Data Science.

**Projects:**

| Project | Algorithm | Language |Solution |
| ------------- | -------------  | ------------ | ------------|
|Credit Card Approval - predict for Approve or Decline applications | Logistic Regression | Python  | [Code](https://github.com/ishanify/Prediction-Model-Projects/blob/master/Predictive%20Model%20Practice%20Projects/CreditCard_Approval_Prediction.ipynb) | 
|Prostate Cancer type detection - predicts Malignant or Benign Cancer | KNN Algorithm | R  | [Code](https://github.com/ishanify/Prediction-Model-Projects/tree/master/Cancer_Prediction_KNN_Algo)|
|Wine quality prediction - predicts High, Medium or Low quality | KNN Algorithm | R | [Code](https://github.com/ishanify/Prediction-Model-Projects/blob/master/Wine_prediction_KNN.ipynb) | 

### I follow this approach to build prediction model:
- Explore data, observe it's characteristics
- Check for missing values and outliers
- Clean the data if there are missing values and/or outliers (This is important for predictive analysis)
- Normalizing the numerical variables if the values are in wide range
  - > (x - min(x)) / (max(x) - min(x))
- Check for class imbalance in the target variable
  - Correct the imbalance using some techniques such as Random oversampling, ROSE, SMOTE etc.
  - Depending on the characteristics of the imbalanced data set, the most effective techniques will vary  
  - For example, **SMOTE** avoids overfitting by inducing synthetic data 
- Dividing the dataset into training and test sets, generally 70:30 ratio
- Training the BEST prediction model by changing various parameters
- **Evaluation of the model**

  | Performace Metric | Description |
  | ----------------- | ----------------- |
  | Accuracy | True Positives/ total observations |
  | Precision | TP / (TP + FP)
  | Recall  | TP / (TP + FN)
  | Sensitivity & Specificity||
  | ROC | |
