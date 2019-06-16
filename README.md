# Prediction-Model-Projects
I have created many prediction projects on different data sets. Each dataset is of a different type.
As a general strategy to perform predictive analysis, I have followed these steps:
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
