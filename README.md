# ML-Project
 
# ML-Project-Campus-Recruitment
## About Dataset

This data set consists of Placement data of students in a XYZ campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students

This dataset is available in kaggle at: https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement

This dataset mainly aims to answer the following questions-

Which factor influenced a candidate in getting placed?

Does percentage matters for one to get placed?

Which degree specialization is much demanded by corporate?


## About Model

### Preprocessing-
To analyse the data first various plots have been made to get the understanding of the data. Then EDA has been done on the data including steps like  ,skewness correction, label encoding and one-hot encoding.

### Feature Enginering-
Used results of mutual information test if used to determine the best set of features, Shown that the dataset is too small hence Logistic Regression would overfit the data and even the Random Forest would also over fit the data and the test results show that Random Forest performs about 76 % accuracy on test data and 100 % on Training Data .


### Model-
The data analysis mainly aims to estimate   Placement status using other features to answer the questions described above. To do that we use Logistic Regression as it didnot over fit the data as to determine Placement status, which is a classification problem we have used various classification model  and finally decided on Logistic Regression.

All the model are compared with best results being-

Placement status- 90.43% accuracy (Logistic Regression)
