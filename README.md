# Loan-Prediction-using-Machine-Learning

# Problem Statement
A financial company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 


# Approach
 
 1. Have done Exploratory Data Analysis to find the relationships between various features
 2. Trained Logistic Regression, Random Forest, XgBoost algorithms on Training Dataset
 3. XgBoost > Random Forest > Logistic Regression ( on the basis of Model Performance)
 4. Applied GridSearchCV and 5-fold Cross- Validation for getting better performance
 
 
 ## Guide to Repository
 # DataSet
 1. train.csv = CSV File for training Dataset
 
     Variable 	Description
     
     
      Column Name | Meaning
    ------------ | -------------
    Loan_ID |	Unique Loan ID
    Gender |	Male/ Female
    Married |	Applicant married (Y/N)
    Dependents |	Number of dependents
    Education |	Applicant Education (Graduate/ Under Graduate)
    Self_Employed |	Self employed (Y/N)
    ApplicantIncome |	Applicant income
    CoapplicantIncome |	Coapplicant income
    LoanAmount |	Loan amount in thousands
    Loan_Amount_Term |	Term of loan in months
    Credit_History |	credit history meets guidelines
    Property_Area |	Urban/ Semi Urban/ Rural
    Loan_Status |	(Target) Loan approved (Y/N)
    
 3. test.csv = CSV File for test datset
    Features in Dataset
    
     Column Name | Meaning
    ------------ | -------------
    Loan_ID |	Unique Loan ID
    Gender |	Male/ Female
    Married |	Applicant married (Y/N)
    Dependents |	Number of dependents
    Education |	Applicant Education (Graduate/ Under Graduate)
    Self_Employed |	Self employed (Y/N)
    ApplicantIncome |	Applicant income
    CoapplicantIncome |	Coapplicant income
    LoanAmount |	Loan amount in thousands
    Loan_Amount_Term |	Term of loan in months
    Credit_History |	credit history meets guidelines
    Property_Area |	Urban/ Semi Urban/ Rural

# Models
1. EDA.ipynb = Data Analysis part code in Jupyter Notebook
2. Model.ipynb = Trained models and their accuracy score on Training Dataset

 
