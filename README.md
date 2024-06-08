In this case study my objective is to predict the likelihood of loan approval based on the given features. For this purpose I have used the loan approval dataset from Kaggle. 
This dataset is a collection of financial records and associated information used to determine the eligibility of individuals for obtaining loans from a lending institution. 
It includes various factors such as cibil score, income, employment status, loan term, loan amount, assets value, and loan status.

**Dataset**

loan_id: Unique IDs

no_of_dependents: Number of Dependents of the Applicant

education: Education level of the Applicant

self_employed: Employment Status of the Applicant, whether self-employed(=Yes), or not

income_annum: Annual Income of the Applicant

loan_amount: Loan Amount applied for

loan_term: Loan Term in Years

cibil_score: Credit Score of the applicant

residential_assets_value: Monetary valuation of residential propertie(s) of the applicant. Negative values implies the applicant is staying on rent

commercial_assets_value: Monetary valuation of commercial propertie(s) of the applicant

luxury_assets_value: Monetary valuation of luxury propertie(s) of the applicant

bank_asset_value: Valuation of total assets in bank account(s) of the applicant

loan_status: Status of loan, whether Approved or Rejected

In this project I have:

Outlier Capping

One Hot Encoded the categorical variables

Standardization(Z-Score Normalization)

Used PowerTransformer on relevant columns to make them normally distributed

Used Logistic Regression for prediction

And, I did all of this using scikit-learn pipelines:

Please refer to ipynb file for the detailed code. 

PS: This is an ongoing project and I hope to add to it further, specifically trying out other algorithms and comparing them.
