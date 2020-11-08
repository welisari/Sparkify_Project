# Capstone-Project
This is my Capstone project which is a part of the Data Scientist Nanodegree Program by Udacity. 


## Project Structure
------
1. [Project Overview](#ProjectOverview)
2. [Project Statement](#ProjectStatement)
3. [Metrics](#Metrics)
4. [Installation](#Installation)
5. [Results and Report](#Results)
6. [Acknowledgements](#ack)

------
## Project Overview <a name="ProjectOverview"></a> 
It is basically about a fictional music streaming company called Sparkify, similar to companies like Spotify. We go through the working on a sample dataset of Sparkify users 
to analyse relevant fetures for predictiong customer churn and build and evaluate machine learning models using Apache Spark^s PySpark API and PySpark ML libraries.
I 

## Project Statement <a name="ProjectStatement"></a> 
The goal of this project is to create an end-to-end prediction model of churn users of the Sparkify music application; the tasks involved are the following:
1. Preprocessing (load, clean, and transform) the raw dataset in json format with PySpark
2. Analyze the data to define the set of features which can be used to train a predictive model
3. Train classifiers that can determine of a user is churned or not by using Apache Spark Machine Learning framework
4. Select the best and improve the model to get higher results
5. Present the results in a report in Medium blog post([this post](https://...) of the end-to-end process to build an ML model in Apache Spark Machine Learning.

## Evaluation
1. **F-1 score** is a measure of a test's accuracy. It considers both the precision p and recall r of the test to compute the score. This traditional F-measure or balanced F-score is the harmonic mean of precision and recall. F-1 = 2 x (precision x recall) / (precision + recall)
2. **Accuracy** is a common metric for binary classifiers; it takes into account both true positives and true negatives with equal weight: accuracy = (true_positive + true_negatives)/dataset_size.

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

## Results <a name="Results"></a>
The final churn prediction model gets the F-1 score of 85% and Accuracy of 87%.
The report of the this project is presented in this blog post [....](https:...).

## Acknowledgements <a name="ack"></a>
The 'mini-sparkify-event-data.json' dataset has been provided by  ([Udacity](https://www.udacity.com/)
