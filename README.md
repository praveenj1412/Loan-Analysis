# Loan-Analysis
This project is for analyzing and predicting the approval of the loan using the given data by implementing machine learning techniques in the Pyspark environment.

## Dataset Description
|Columns|Description|
|-------|-----------|
|loan_id|Unique identifier for each loan|
|no_of_dependents|Number of dependents the borrower has|
|education| The educational level of the borrower|
|self_employed|Employment status of the borrower |
|income_annum|The annual income of the borrower|
|loan_amount|The amount of money borrowed by the borrower|
|loan_term|The duration of the loan in terms of months or years|
|cibil_score|The Credit Information Bureau (India) Limited (CIBIL) score of the borrower, which is a measure of their creditworthiness|
|residential_assets_value| The value of residential assets owned by the borrower|
|commercial_assets_value|  The value of commercial assets owned by the borrower|
|luxury_assets_value|The value of luxury assets owned by the borrower|
|bank_asset_value|The value of assets held in bank accounts by the borrower|
|loan_status|The status of the loan|

The dataset is collected from kaggle.

## Algorithms used
- Logistic Regression.
- Random forest classifier.

  The algorithms are performed in the Pyspark environment.
## Performance Analysis
Area Under the Curve and Accuracy are the measures used for checking the performance of the model.
### Logistic Regression
- AUC : 97%
- Random Forest : 90%
### Random Forest Classifier
- AUC : 99%
- Random Forest : 96%
