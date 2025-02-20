# Garment-Employees-ML-Regression-Project
Regression Machine Learning Project: Predicting Productivity

Performed an ML regression task to predict actual productivity using 14 features such as team size, overtime, incentives, and idle time.

## Project Workflow:
Exploratory Data Analysis (EDA):

Multivariate analysis & correlation exploration

### Feature Engineering:
#### Created new variables:

`overtime_per_workers = over_time / no_of_workers`

`overtime_per_wip = over_time / wip`

`incentive_per_person = incentive / no_of_workers`
 
### Data Preprocessing:

Handled missing values via median imputation

One-hot encoding for categorical variables

Feature scaling & created pipeline functions
 
### Modeling & Evaluation:

Performed ML with Linear Regression, Decision Trees, and Random Forest models.

Used stratified splitting to maintain data proportionality

Applied cross-validation & hyperparameter tuning

Identified feature importance

Final model achieved RMSE of 0.156

### References.

https://github.com/ageron/handson-ml2/blob/master/02_end_to_end_machine_learning_project.ipynb

https://www.youtube.com/watch?v=-dK_80wu4xs
