---
layout: project
type: project
image: img/covid.jpeg
title: "COVID-19 Death Analysis"
date: 2022-02-12
published: true
labels:
  - Python
  - Jupyter
  - Data Science
  - Machine Learning
  - GitHub
summary: "A data science project that analyzes COVID-19 deaths"
---

<img class="img-fluid" src="../img/covid-banner.jpeg">

This is a data science project that examines the factors that cause a COVID-19 case to result in a death. The dataset is a sample taken from the CDC: https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/n8mc-b4w4.  After trying many different machine learning models, the results of the best model (XGBoost) was shown along with some analysis for insight.

This project demonstrates:

- Data exploration and wrangling
- Techniques to impute missing data
- Encoding categorical variables and standardizing numerical variables
- Building a classification model using scikit learn
- Optimizing model hyperparameters
- Evaluating model performance using accuracy, ROC, and AUC
- Interpretation of significant features in the model
- Data visualization

The model was able to achieve an AUC of 0.9835 in predicting whether a COVID-19 case resulted in a death.  One of the biggest challenges with this project was the data wrangling and preparation.  In particular, there was a lot of missing data, and one of the reasons XGBoost was chosen as the final model was because of its robustness to blank values.  In the analysis of top feature variables, age was shown the to the most significant predictor of death, where being age 65+ significantly increased the risk of death from COVID-19.

Source: <a href="https://github.com/junkim1519/Covid19_Analysis"><i class="large github icon "></i>junkim1519/Covid19_Analysis</a>
