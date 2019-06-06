# Predicting Prostate Cancer using KNN classifier
### Objective
The to build a prediction model for predicting the type on Cancer based on other independent variables. 
KNN algorithm is used in R with ggplot2, class and gmodels packages.

### Data Preparation
The data set contains information 100 patients who have been diagnosed with either Malignant (M) or Benign (B) cancer.
Before applying any ML algorithm it is important to clean and normalize the data. The data was checked for missing values and normalized because the values of the variables were not in same range.
Then the data was divided into train and test set with 65% data for training and rest for testing the model.

### Prediction Model Observations

Optimim number of k were identified by applying the KNN multiple times on the training dataset.
For k = 6 the model predicted quite accurately. This might not be the best k because the data set is not big enough and training set is randomly sampled.

This is the confusion matrix below for k=6. 
Cases predicted correctly = 30 out of 35. 
False Positives = 3 (Cases that were actually Benign but predicted as Malignant)
False Negatives = 2 (Cases that were actually Malignant but predicted as Benign)

       

          | final_model 
      test_label |    Benign | Malignant | Row Total | 
    -------------|-----------|-----------|-----------|
          Benign |         9 |         3 |        12 | 
                 |     0.750 |     0.250 |     0.343 | 
                 |     0.818 |     0.125 |           | 
                 |     0.257 |     0.086 |           | 
    -------------|-----------|-----------|-----------|
       Malignant |         2 |        21 |        23 | 
                 |     0.087 |     0.913 |     0.657 | 
                 |     0.182 |     0.875 |           | 
                 |     0.057 |     0.600 |           | 
    -------------|-----------|-----------|-----------|
    Column Total |        11 |        24 |        35 | 
                 |     0.314 |     0.686 |           | 
    -------------|-----------|-----------|-----------|
         

### Conclusion
Considering the small size of the dataset, the results were satisfactory.
KNN classification model predicted results with accuracy = 85.71%
It would be interesting to build prediction models for big data sets.
As I learn new concepts in Data Science it is likely that I will revisit this dataset, to test other algorithms.




