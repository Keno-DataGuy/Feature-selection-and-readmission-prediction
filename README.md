# Feature-selection-and-readmission-prediction

Given the high rate of hospital readmissions among heart failure patients, proper risk assessment is essential for clinical decision-making and patient management. This research aims to evaluate the effectiveness of various pre-processing and post-processing methods for feature selection in predicting heart failure patient re-admission over a six-month period. Utilizing data from the PhysioNet database, this study addresses the critical need for feature selection techniques to improve the performance of machine learning models in the context of heart failure patient care.

#### Dataset
Data Source for Study:

-Database: Patient-specific, freely accessible database

-Origin: PhysioNet data portal (https://physionet.org/content/heart-failure-zigong/1.3/)

-Accessed: 21 June 2023

-References: Goldberger et al. 2000

-Patients: 2008 heart failure patients

-Fields: 167 features

-Hospital: Fourth People’s Hospital of Zigong City, Sichuan, China

-Time Frame: December 2016 to June 2019

-Dataset Authors: Zhang et al. 2020; Zhang et al. 2021

This study has presented three pre-processing feature selection techniques (correlation analysis, mutual information gain and variance thresholding), and then 3 post-processing feature selection techniques (recursive feature elimination, borutaShap, borutaShap for XGBoosting algorithm). We also employed four machine learning algorithms (decision tree, random forest, gradient boosting, and multilayer perceptron) to predict heart failure patient re-admission over a six-month period.

Results showed that MLP in combination with the variance thresholding achieved an accuracy and F1-score of 62.2% and 0.481 respectively. Gradient boosting in combination with information gain achieved an accuracy and F1-score of 64.4% and 0.476 respectively. DT in combination with correlation analysis achieved an accuracy and F1-score of 57.7% and 0.479 respectively. Random forest in combination with information gain achieved an accuracy and F1-score of 63.1% and 0.366 respectively. XGBoost in combination with borutaSHAP achieved an accuracy and F1-score of 60% and 0.469 respectively.

