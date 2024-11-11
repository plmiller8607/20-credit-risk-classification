# 20-credit-risk-classification
Supervised learning challenge

Overview of the Analysis
This Challenge uses machine learning to train and evaluate a model based on loan risk. It utilizes a historical dataset of lending activity from a peer-to-peer lending services company. The dataset contained 77536 rows and 8 columns. The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.  

Specifically, Supervised Learning using a Logistic Regression Model was created to make a prediction using probability to place a loan in an output classification labeled “0” indicating a loan_status of healthy or an output classification labeled “1” indicating a loan_status in high risk of default.  

The results of the Logistic Regression Model were examined by creating a confusion matrix and by generating a classification report.

**Results**

For predicting healthy loans (class 0), this machine learning model arrived at scores of 1.00 for precision, 0.99 for recall, and 1.00 for f1. These results are very high.

For predicting high-risk loans (class 1), this machine learnining model arrived at scores of 0.85 for precision, 0.91 for recall, and 0.88 for f1. The lower precision and recall scores indicate a tendency toward false positives.

Therefore, this model is highly accurate in predicting healthy loans, with near-perfect scores. However, it’s slightly less precise for high-risk loans, because it is more likely to produce false positives than false negatives. This model is very reliable indicating that the training data provided what was needed to make accurate predictions, but it is slightly better at identifying healthy loans than high-risk loans. I would recommend this model if it continued to perform in this manner with more trials using different datasets.

                


