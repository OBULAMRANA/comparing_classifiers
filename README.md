#  Assignment 17.1: Comparing Classifiers
## Author: Rana Obulam
### Project Overview
Compare the performance of the 4 classification algorithms and pridict the term deposits on features.

  K Nearest Neighbor
  
  Logistic Regression
  
  Decision Trees
  
  Support Vector Machines
  
### Dataset information 
The assignment data is to analyze the  banking institution collection of the results of multiple marketing campaigns.

Data Source: [https://github.com/OBULAMRANA/accept_coupon/blob/main/coupons.csv](https://github.com/OBULAMRANA/comparing_classifiers/blob/main/bank-additional.csv)

Python Code: [https://github.com/OBULAMRANA/accept_coupon/blob/main/accept_coupon.ipynb](https://github.com/OBULAMRANA/comparing_classifiers/blob/main/prompt_III.ipynb)


### Data Understanding & Cleaning
This dataset has 4119 records. We cleaned the data by removing the columns ('duration', 'contact', 'month', 'day_of_week', 'emp.var.rate', 'cons.price.idx', 'cons.conf.idx', 'euribor3m', 'nr.employed') which are not relavent for analysis.And also the rows ('education_unknown', 'default_unknown', 'housing_unknown','loan_unknown') from catagorical data.

### Baseline Modeling

### Creating 4 models for comparision
Below 4 clasification models created for comparision

K Nearest Neighbor

Logistic Regression

Decision Tree

Support Vector Machine


### Tuning the 4 models for comparision

Tuned the models K Nearest Neighbor,Logistic Regression,Decision Tree, Support Vector Machine to improve the performance using GridSearchCV

### Conclusion & Recommendation
Published the results of the perfomance for each model and evaluated based on the accuracty. By comparing the info before tuning and after, we saw the improments in accuracy after tuning. KNN and LogisticRegression are recommended because they have best accuracy. SVM is also good but it is taking time and resources.
