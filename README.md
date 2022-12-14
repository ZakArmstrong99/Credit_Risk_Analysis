# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
The purpose of this analysis was to create models using sklearn and imblearn in order to see what influences credit risk for loans. More specifically, the goal was to see if random oversampling, SMOTE oversampling, undersampling, SMOTEENN sampling, balanced random forest classifier, or the easy ensemble adaboost classifier is the most accurate. In order to create the models the data was split using train_test_split to make predictions using the sampling methods and classifiers. The balanced accuracy scores and classification reports provide the information to decide which of the models are the most accurate. 


## Results:
- The balanced accuracy score with random oversampling is .625, the precision score is 0.99, and the recall score is 0.65.
![Naive_Random_Oversampling](https://user-images.githubusercontent.com/107213807/194166270-b4857e10-3424-46be-8fa3-fcb7b6f8d39e.png)

- The balanced accuracy score with SMOTE oversampling is .651, the precision score is 0.99, and the recall score is 0.66.
![SMOTE_Oversampling](https://user-images.githubusercontent.com/107213807/194166318-31f0a786-eb5e-4b92-8757-fab25f67465d.png)

- The balanced accuracy score with undersampling is .510, the precision score is 0.99, and the recall score is 0.44.
![Undersampling](https://user-images.githubusercontent.com/107213807/194166353-d88a6a11-6de4-4632-8d03-6b947d4609d5.png)

- The balanced accuracy score with SMOTEENN sampling is .628, the precision score is 0.99, and the recall score is 0.54.
![SMOTEENN_Sampling](https://user-images.githubusercontent.com/107213807/194166401-42003f01-d431-40e4-beab-3285571029e1.png)

- The balanced accuracy score with Balanced Random Forest Classifier is .789, the precision score is 0.99, and the recall score is 0.87.
![Balanced_Random_Forest_Classifier](https://user-images.githubusercontent.com/107213807/194166695-73fe7490-300b-4c7c-bbf7-b358eef9c65a.png)

- The balanced accuracy score with Easy Ensemble Adaboost Classifier is .931, the precision score is 0.99, and the recall score is 0.94.
![EEC_Classifier](https://user-images.githubusercontent.com/107213807/194166455-4baf38d8-6e3d-41ae-af96-30131c8e556b.png)



## Summary:
Looking at the results, we can see that the EEC model is the most accurate and the undersampling model was the least accurate. All of the models have precision scores of 0.99, but have different recall scores. The recall score of the undersampling model was the lowest, which led to its accuracy score being lower than the rest. With that being said, the EEC model had a recall score of 0.94 making it my recommendation of the model to use. Out of the sampling models the SMOTE oversampling model had the best score, but in comparison to the classifier models the results are not as accurate. This is why I recommend using the EEC model.

