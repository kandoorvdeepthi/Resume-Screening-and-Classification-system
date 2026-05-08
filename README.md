# Resume-Screening-and-Classification-system
This Resume Screening and Classification System leverages NLP and Machine Learning to automate recruitment. Built with Python and Scikit-Learn, it processes raw resume text , using a Logistic Regression model to categorize candidates into roles like IT, HR, or Finance. This streamlines hiring by reducing manual screening effort.

Overview
This repository contains a machine learning pipeline designed to automate the screening of resumes. It classifies resumes into various professional categories (e.g., HR, Information Technology, Healthcare) to help recruiters quickly identify relevant candidates.

Dataset
The project uses a dataset named Resume.csv. It includes the following key columns:  
1. ID: Unique identifier for each resume.  
2. Resume_str: Raw text content of the resume.  
3. Category: The professional field or job role associated with the resume (e.g., HR, Business Development).

Project Workflow
1. Data Loading: Importing the dataset using pandas.  
2. Exploratory Data Analysis (EDA): Visualizing the distribution of categories using matplotlib and seaborn.  
3. Data Preprocessing: Cleaning the text and preparing it for vectorization.  
4. Model Training: Implementing a OneVsRestClassifier with a LogisticRegression estimator.  
5. Evaluation: Testing the model's performance on a hold-out test set to determine accuracy.

Technical Stack
1. Language: Python.  
2. Libraries:
3. pandas & numpy for data manipulation.  
4. scikit-learn for machine learning and model evaluation.  
5. matplotlib & seaborn for data visualization.

Usage
Open the Jupyter Notebook resume_screening - Copy.ipynb to view the full implementation, from data ingestion to model prediction. Ensure that Resume.csv is in the same directory as the notebook before running the cells.
