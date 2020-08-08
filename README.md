# Sparkify
Sparkify is a music streaming service just as Spotify and Pandora.  The data provided is user log of the service and additional information on users. We analyzed log and build models to identify customers who are highly likely to churn and thus, send marketing offers to them to prevent them from churning.   We also did EDA to establish features, and trained 3 machine learning classification models.

## Table of Contents
1. Dependencies
2. Motivation
3. Files Description
4. Results
5. Acknowledgements

## Dependencies:
The following libraries are needed to implement this project:

Python
Pandas
Matplotlib
Seaborn
PySpark
Spark


## Motivation:
Sparkify is a music streaming service just as Spotify and Pandora.  The data provided is user log of the service for the past few months. It contains some basic information about the users as well as data about a particular action they have taken. We can identify when a user churned through the action of account cancellation.

## Files Description:

Sparkify.ipynb: The notebook where we do all the preprocessing, feature engineering and modelling.

## Results:

Implemented end to end machine learning project in predicting customer churn. All the necessary preprocessing which includes checking for null and duplicate values as well as converting time stamp and registration time to a more cleaner format are done. 9 features and the target churn label are created. Trained 3 kinds of classification models on our data: RandomForest, Support Vector Machines and Gradient Boosted Trees. Compared performance of all three models and GBT outperformed the rest and so selected it as our final model along with doing some grid search to improve the performance of the model.

The final metrics for our Gradient Boosted Trees Classifier are as follows:
F-1 Score is 0.782608695652174
Accuracy is 0.7863487611033193

Please check my blog post to get more details, here is the [link](https://medium.com/@indraneeldb1993/predict-customer-churn-using-pyspark-7741c64ede07?sk=9c8ee5322eef35ebff273dc55b588f9a).

## Acknowledgements
Udacity has to be acknowledged for giving me this wonderful project.
