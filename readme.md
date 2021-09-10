# Projects_Intro to Machine Learning with Pytorch Nanodegree Program
This is the project repository for Udacity's Machine Learning course. I will keep update when I finish other projects. 

## Finding Donors for Charity ML
In this project, I applied supervised learning techniques to predict who most likely to donate to CharityML. The data was collected for the U.S. census to help CharityML (a fictitious charity organization). 

After exploring the data sets, I built three classification models (Guassian Naive Bayes, Logistic Regression and Random Forests) and evaluated them by comparing accuaracy score and f-beta scores. Given the results and time efficiency, I chose logistic regression for my final model. 

Finally, I found the top 5 important predictors by using sklearn's feature importances and compared the model with full data and the model with only top 5 features. The model with full data was better but if the training time was an issue, I would choose to reduce some features because the differences of two models' performces were negligible. 


## Fil Structure

The file is described below:

```
Data/
    - census.csv
    - example_submission.csv
    - test_census.csv
- finding_donors.ipynb: notebook for finding donors project
- report.html: report for finding donors project
- visuals.py: provided by Udacity to make visualization
```


## Acknowledge
The project, data, and some codes are provided by Udacity. 