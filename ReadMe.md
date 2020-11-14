# Data Scientist Capstone Project
This is my Capstone project which is a part of the Data Scientist Nanodegree Program by Udacity. 


## Project Structure
------
1. [Overview](#Overview)
2. [Project Statement](#ProjectStatement)
3. [Metrics](#Metrics)
4. [Results](#Results)
5. [Installation](#Installation)
6. [Acknowledgements](#ack)

------
## Overview <a name="Overview"></a> 
It is basically about a fictional music streaming company called Sparkify, similar to companies like Spotify. We go through the working on a sample dataset of Sparkify users 
to analyse relevant fetures for predictiong customer churn and build and evaluate machine learning models using Apache Spark's PySpark API and PySpark ML libraries.

## Project Statement <a name="ProjectStatement"></a> 
Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data. Thus, the following tasks have been accomplished to 
build an end-to-end prediction model of churn users of the interested music application:
- Preprocessing (load, clean, and transform) the raw dataset in json format with PySpark
- Analyze the data to define the set of features which can be used to train a predictive model
- Train classifiers that can determine of a user is churned or not by using Apache Spark Machine Learning framework
- Select the best and improve the model to get higher results
- Present the results in a report in Medium blog post[this post](https://medium.com/@velisari/sparkify-user-churn-prediction-6c727699cac4)

## Evaluation
1. **F-1 score** is a measure of a test's accuracy. It considers both the precision p and recall r of the test to compute the score. This traditional F-measure or balanced F-score is the harmonic mean of precision and recall. F-1 = 2 x (precision x recall) / (precision + recall)
2. **Accuracy** is a common metric for binary classifiers; it takes into account both true positives and true negatives with equal weight: accuracy = (true_positive + true_negatives)/dataset_size.

## Results <a name="Results"></a>
The final churn prediction model gets the F-1 score of 85% and Accuracy of 87%.
The report of the this project is presented in this blog post [User Churn Prediction for a Digital Music Service Using PySpark](https://medium.com/@velisari/sparkify-user-churn-prediction-6c727699cac4).

## Installation <a name="Installation"></a>
Reguired installations:
+ Jupyter Notebooks
+ Python 3.6.7

Required packages: 
+ PySpark 2.4.4 (PySpark.sql and PySpark.ml)
+ Pandas
+ Datetime
+ Matplotlib
+ Seaborn  

## Acknowledgements <a name="ack"></a>
The 'mini-sparkify-event-data.json' dataset has been provided by  ([Udacity](https://www.udacity.com/)
