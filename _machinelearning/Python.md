---
title: "How Non-genetic Genetic Affect Semen Quality - An Analysis Using Simple Machine Learning Models"
collection: machinelearning
permalink: /machinelearning/machinelearning-semen

---
## About the project
  The project investigates how some non-genetic factors such as medical history and lifestyle affect semen quality using machine learning algorithms.

## Goal
  The project aims to find the most suitable classification algorithm to assist the sperm quality assessment.

## Data
  The data was taken from UCI machine learning model repository.

## Outcomes
  Overall, the results indicated that combinations of numbers of hours sitting in a day, childish diseases, surgical intervention, alcohol consumptions and accident are useful in predicting which individuals have normal semen. The report concludes that these non-genetic factors were only useful in assisting the semen evaluation process, the models cannot replace semen evaluation at this stage.

## Limitations
  The data was used for the project was small; the majority of the data (43/50) was cases with normal sperm quality. Therefore, the usability of the models in predicting abnormal cases is not significant.

## What I've learned from this project
  1. Model fitting:
    The processing of choosing the "best" model is highly dependant on the research question. In this specific situation, the KNN model outperforms in detecting normal quality semen, however, the Decision tree is doing much better at detecting abnormal cases (3/7) compare to (0/7) of that from KNN.  
  2. Expert knowledge:
    The experiment can improve greatly with knowledge regarding the importance of the variables in the clinical context. In addition, we can add more dimensions to the experiment by using other datasets; which may help to improve the usability of the models.

You can [download the written report](https://minhphan88.github.io/assets/mlreport1.pdf) here.
You can [download the Jupiter Notebook pdf](https://minhphan88.github.io/assets/mlcode1.pdf) here.

The project demonstrates the ability to work with Python libraries including *Matplotlib, NumPy, Pandas, Seaborn and Sklearn(KNN, Decision Tree and Random Forest)*
