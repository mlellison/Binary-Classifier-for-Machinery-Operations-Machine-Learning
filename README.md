# Binary-Classifier-for-Machinery-Operations-Machine-Learning

-----------------------------------------------------------------------------------------------------------------------------------------------------------
1.) What was the problem?

Given (simulated) manufacturing control data and are tasked to predict whether the machine is in state 0 or state 1,
consider these dataset as 3D printing projects, predicting the success rate (0 or 1) before actually printing, can save tons of cost, materials, time, etc.
The column names are anonymised, it is a good practice to boost accuracy without domain knowledge.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
2.) How to solve them?

Solving it by Exploratory data analysis (EDA), Feature Engineering, and Supervised Learning,
built model with random forest, logistic regression, decision tree, xgboost.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
3.) What was the outcome?

Achieved 97% accurracy with xgboost after Hyper-parameter tuning (HPT)
Inside 900,000 rows of data, nearly 50% is predicted as fail, in this case, nearly 450,000 failed 3D printing projects are being avoided to print out,
if each printing cost HKD 1, and took 1 second to finish, HKD 450,000 and 5 days of printing have been saved.
