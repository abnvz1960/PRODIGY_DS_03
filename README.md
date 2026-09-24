# PRODIGY_DS_03
# Task 3: Decision Tree for Credit Risk Prediction  Part of the Prodigy Infotech Data Science Internship.  ## Objective Build a decision tree classifier to predict loan default using demographic and financial characteristics of borrowers.  ## Dataset Credit Risk dataset (CSV).  ## Approach - Median imputation for employment length and loan 
# Task 3: Decision Tree for Credit Risk Prediction

Part of the Prodigy Infotech Data Science Internship.

## Objective
Build a decision tree classifier to predict loan default using
demographic and financial characteristics of borrowers.

## Dataset
Credit Risk dataset (CSV).

## Approach
- Median imputation for employment length and loan interest rate
- One-hot encoding of categorical features
- Stratified 80/20 train-test split
- DecisionTreeClassifier (gini, max_depth=5, min_samples_split=20)
- Evaluated with accuracy, classification report and confusion matrix
- Visualized the full decision tree

## Results
- Accuracy: ~90.8%
- High precision on non-default (safe) loans; recall on defaults ~57%
- Loan-to-income ratio was the strongest predictor (~35% importance)

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
