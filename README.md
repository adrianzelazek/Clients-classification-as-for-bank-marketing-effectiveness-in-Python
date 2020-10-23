# Clients classification - bank marketing effectiveness in Python
### Author: Adrian Żelazek

In this project was used dataset related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The dataset contains 41188 observations as well as 21 variables. 

The target of this project is to build and evaluate classification model to predict whether the client will subscribe to a term deposit. The project includes exploration and visualization of data, snalysis of normal distiburion, outliers removal, dummy coding, oversampling by SMOTE and features selection by RFE selected features were evaluated based on p-value and VIF indicator. All selected values were finally used in model biulding. Model was evaluated by: Confusion Matrix, ROC curve, AUC, Accumulative protif curve, Forecasting error of classes, Classification Report and indicators: Accuracy, Recall, Precision, F1. Furthermore, results of training and test datasets were compared with each other to exclude possible of overfitting.

This project was developed for the purpose of practicing machine learning and data mining in Python.
Source of dataset: UCI Machine Learning Repository

##### It is preferred to run/view the project via Jupyter Notebook (.ipynb), sometimes it is required to press "Reload" to load the file, than via a browser (HTML). To see the HTML version you first need to download the HTML file and then run it in your browser.

### Programming language and platform
* Python - version : 3.7.4
* Jupyter Notebook

### Libraries
* Pandas version is 0.25.1
* Scipy version is 1.5.2
* Scikit-learn is 0.23.2
* Statsmodels is 0.10.1
* Numpy version is 1.16.5
* Matplotlib version is 3.1.2
* Seaborn version is 0.9.0

### Algorithms
* Notmal test
* dummy coding
* SMOTE
* RFE
* VIF
* Logit
* Logistic Regression

### Methods of model evaluation
* Confusion Matrix 
* ROC curve
* AUC
* Accumulative protif curve
* Forecasting error of classes
* Classification Report and indicators: Accuracy, Recall, Precision, F1

### Results
Classification Logistic Regression presents the following results:
* AUC = 0.95
* Percentage of correct forecasts = 0.89
* Percentage of positively classified positive results = 0.88
* Percentage of correct positive forecasts = 0.91
* Harmonic average of precision and sensitivity = 0.89


