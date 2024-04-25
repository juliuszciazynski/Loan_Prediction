Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form.
These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others.
To automate this process, they have given a problem to identify the customers segments,
those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

DESCRIPTION OF DATA
Loan_ID	: Loan reference number (unique ID) 
Gender : Applicant gender (Male or Female) 
Married : Applicant marital status (Married or not married) 
Dependents : Number of family members 
Education : Applicant education/qualification (graduate or not graduate) 
Self_Employed : Applicant employment status 
ApplicantIncome	: Applicant's monthly salary/income 
CoapplicantIncome : Additional applicant's monthly salary/income	
LoanAmount	: Loan amount in cash 
Loan_Amount_Term : The loan's repayment period (in days) 
Credit_History : Records of previous credit history
Property_Area : The location of property 
Loan_Status	: Status of loan (Y: accepted, N: not accepted)


STEPS OF THE PROJECT:
1) Downloading data
2) Data exploration, checking categorical and numerical data
3) Data Cleaning and preprocessing, dealing with missing values
4) Dealing with unbalanced data (SMOTE)
5) Principal component analysis
6) Creating Logistic Regression, KNN, Support Vector Machine, Naive Bayes, Decision Tree, Random Forest models, comparing their accuracies with different values of components
7) Things do add: Development of the statistical tests which can lead to more preprocessing, introducing a neural network, testing present models with different parameters
