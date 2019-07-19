# Prediction-Model-Projects
### What this repository contains?
I have created many prediction projects in R and Python on different data sets such as Prostate Cancer, Wine Quality and more. Each project would be a better than the previous one as I learn to apply more advanced concepts of Data Science.

**Projects:**
1. Prostate Cancer Prediction - Model predicts if a patient had Malignant or Benign Cancer (https://github.com/ishanify/Prediction-Model-Projects/tree/master/Cancer_Prediction_KNN_Algo)
2. Wine quality prediction - Model predicts if wine has High, Medium or Low quality  (https://github.com/ishanify/Prediction-Model-Projects/blob/master/Wine_prediction_KNN.ipynb)

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
  - For example in KNN, I found the best fit model by changing value of K.
- **Evaluation of the model**

  | Performace Metric | Description |
  | ----------------- | ----------------- |
  | Accuracy | True Positives/ total observations |
  | Precision | TP / (TP + FP)
  | Recall  | TP / (TP + FN)
  | Sensitivity & Specificity||
  | ROC | |