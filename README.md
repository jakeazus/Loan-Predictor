# Loan Predictor Machine Learning Project

By: _**Nadia Richards, Jake Azus, Noah Goldstein, Perry Reynolds**_
## Background
---
A good friend of ours named Perry, was graduating from Florida State and wanted to move to NYC. Upon graduation he decided that he and a couple friends wanted to buy an apartment in the city rather than rent. In order to do so, he wanted to take out a loan to cover his part of the apartment purchase price. 

When applying for a loan, he spoke with his parents who told him that applying for a loan can affect your credit score. So, before applying for his loan he wanted to do some research to figure out if he'd get approved or not. This was the basis of our project exploration...

We decided to analyze a set of 500+ samples with 12 independent attributes and the impending Y/N loan status of approval. We utilized this data to develop 3 different predictive machine learning models that could ultimately predict whether or not Perry would get his loan!

## Tools and Technology Used for Analysis
---
* VSCode
* Python
* Jupyter Notebook
* Pandas
* Matplotlib
* Sklearn
    * Logistic Regression
    * Decision Trees
    * Random Forest
* NumPy
* Pickle

## Machine Learning Model Details
---
* Developed 3 machine learning models: logistic regression, decision trees, and random forest
* Analyzed 614 loan instances across 12 variables
* Trained and tested all 3 models with a 70% - 30% train, test split 

## Data Source
---
**Loan Prediction Problem Dataset:** see dataset [HERE](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset)

## Predictive Models used
1. Logistic Regression
2. Random Forest
3. Decision Tree

## Summary of Findings
---
#### Key Model Statistics From Emotion Predictor
1. Logistic Regression: ~80%
2. Random Forest: ~70%
3. Decision Tree: ~80%

#### Dataset Exploration

<p align="center"> <img width="550" height="400" src="https://user-images.githubusercontent.com/13200513/116893879-77367580-abff-11eb-99e2-f79c5d491cfd.png"> <img  width="550" height="400" src="https://user-images.githubusercontent.com/13200513/116894161-c1b7f200-abff-11eb-940c-0ed349e948df.png">  </p> 


#### Limitations to Our Data
1. Limited size of model training dataset
2. There were a sizeable amount of null values which had to be removed before training the model, so we lost some sample datapoints

#### Additional Thoughts to be Explored Further
1. Explore additional independent variables
2. Integrate geographic locations to the dataset
3. Further explore the types of loans being given (i.e., risky business venture, cars, property, etc.)
