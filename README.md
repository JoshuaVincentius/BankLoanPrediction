# BankLoanPrediction

This is the notebook file about prediction on customers risk using bank loan history (training) dataset of a banking company. The file includes analysis on customer behavior, prediction modelling, prediction on customers risk flag using test data and business simulation to compare the results if we implement the machine learning model.

The training data itself has 252.000 rows and 13 columns with risk flag as its target variable. Risk flag '0' means 'not risky' and '1' means 'risky'. Meanwhile, the test data has 28.000 rows and 12 columns and it will be used to predict the risk flag using the Machine Learning model that we design.

Column	Description	Type
- income:	Income of the user
- age:	Age of the user
- experience:	Professional experience of the user in years
- profession:	Profession
- married:	Whether married or single
- house_ownership:	Owned or rented or neither
- car_ownership:	Does the person own a car
- current_job_years:	Years of experience in the current job
- current_house_years:	Number of years in the current residence
- city:	City of residence
- state:	State of residence
- risk_flag:	Defaulted on a loan
