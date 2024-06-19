# Loan-Risk-Prediction
The Loan risk prediction model was based on Logistic regression technique of supervised learning in the presence of given dataset.
The risk factor was evaluated and the prediction was generated to determine whether the client is High risk or Low risk if provide loan on the basis of Risk_Flag.
Data Visalization:
Libraries like Matplotlib.pyplot, Seaborn, Sklearn, Tensorflow and Plotly are used for the visualization of data in the forms of:
1. Confusion Matrix: A confusion matrix in machine learning summarizes the predictions of a classification model as follows:
 True Positive (TP): Model predicts positive (high-risk) correctly.
 True Negative (TN): Model predicts negative (low-risk) correctly.
 False Positive (FP): Model predicts positive (high-risk) incorrectly.
 False Negative (FN): Model predicts negative (low-risk) incorrectly.
It helps evaluate the model's performance beyond accuracy, especially in scenarios with imbalanced classes or varying costs of errors.
2. Classification Report: A classification report in machine learning provides precision, recall, F1-score, and support for each class. It summarizes model performance as follows:
 Precision: Proportion of true positive predictions among all positive predictions.
 Recall: Proportion of true positives correctly identified by the model.
 F1-score: Harmonic mean of precision and recall, balancing both metrics.
 Support: Number of occurrences of each class in the dataset.
3. ROC Curve: An ROC (Receiver Operating Characteristic) curve in machine learning visually evaluates the trade-off between true positive rate (sensitivity) and false positive rate (1-specificity) for different threshold values. Key points include:
 True Positive Rate (TPR): Ratio of true positives to all actual positives.
 False Positive Rate (FPR): Ratio of false positives to all actual negatives.
 Threshold: Decision boundary for class prediction, affecting TPR and FPR
To visualize the model’s predictively and accuracy.
The accuracy_score method of sklearn.metrics package is used to describe the model’s 
behavior across all the classes of the dataset.On the basis of observations based on the Classification report we can study that the accuracy score varies as per the classification threshold.
