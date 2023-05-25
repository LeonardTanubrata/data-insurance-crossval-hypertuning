# data-insurance-crossval-hypertuning
build model and hyperparameter tuning for dataset insurance


Metrics & Hyperparameter Tuning**

**Use data 'insurance'**

the best model and hyperparameter to predict insurance costs for each individual based on their characteristics.
1. Do a short EDA to explore the dataset first.
2. Do preprocessing on the features if needed.
3. Perform modeling using lasso regression, knn regressor, and decision tree regressor.<br>
    Algorithm candidate:
    - lasso = Lasso
    - knn = KNeighborsRegressor
    - tree = DecisionTreeRegressor
4. 1 best model based on the cross validation results of the 3 models above.
5. Make predictions on the test set of the selected model (before hyperparameter tuning).
6. Perform hyperparameter tuning on the selected model.
7. Make predictions on the test set of the model with hyperparameter tuning.
8. Compare the performance results of the model before and after tuning.

**Features Description**

- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- charges: Individual medical costs billed by health insurance
