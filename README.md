# Predicting Job Call Back Rate
This repository contains code and data for a project that focuses on predicting the job call back rate based on job and applicant attributes. The goal is to build a model that can help in identifying the factors that contribute to a higher chance of receiving a call back after submitting a job application.

Table of Contents
1. Data Preprocessing
2. EDA for Job
3. EDA for Applicant
4. Model Preprocessing
5. Model Building
6. Model Comparison
  
### Data Preprocessing
In this phase, the raw data is cleaned and prepared for analysis. The following steps are performed during data preprocessing:
* Handling duplicate values
* Removing unnecessary columns
* Handling missing values

### EDA for Job
Exploratory Data Analysis (EDA) is performed on the job-related attributes to gain insights and understand the characteristics of the job postings. The analysis may include the following:
* Distribution of jobs across different cities, industries, and types.
* Proportions of federal contractors and equal opportunity employers.
* Analysis of job requirements, such as communication skills, education level, minimum experience, computer skills, etc.
* Correlation analysis between job attributes and the callback rate.

### EDA for Applicant
EDA is also conducted on the applicant-related attributes to understand the characteristics of the applicants. The analysis may include:
* Distribution of applicants by race, gender, college degree, etc.
* Examination of applicant attributes such as years of college, honors, work experience, computer skills, special skills, military experience, etc.
* Analysis of email address availability and resume quality.
* Correlation analysis between applicant attributes and the callback rate.

### Model Preprocessing
* Encoding categorical variables: Convert categorical variables into numerical representations using one-hot encoding method.
* Dependent feature: Seperating dependent and independent feature
* Data splitting: Separate the dataset into training and testing sets.
* Creating user-defined function:
  - Model training: Fit the chosen algorithm on the training data.
  - ROC: Plotting ROC AUC curve.
  - Model evaluation: Evaluate the model's performance on the testing data using appropriate metrics, such as accuracy, precision, recall, or F1 score.


### Model Building
In this phase, various machine learning algorithms are applied to build predictive models for job callback rate. The algorithms that are applied are:
* Logistic Regression
* Logistic Regression (using SGD)
* Decision Tree
* Decision Tree with Pruning
* Random Forest
* Random Forest with Pruning
* Bagging Ensemble
* AdaBoost Ensemble
* XGBoost Ensemble
* Naive Bayes
* K-Nearest Neighbors (KNN)
* Support Vector Machines (SVM)



### Model comparison:
After applying all the algorithms, a model comparison is conducted to assess the performance of each model. The comparison may include the following aspects:
* Evaluation metrics: Compare the performance metrics like train score, test score, AUC score, precision, Recall, and f1-score of different models to identify the most effective one.
* Visualizations: Present visualizations, such as confusion matrices or ROC curves, to better understand the performance of each model.

Feel free to explore the code and data provided in this repository. The project's main objective is to understand and predict job callback rates, which can provide valuable insights for both job seekers and employers in optimizing the hiring process.
