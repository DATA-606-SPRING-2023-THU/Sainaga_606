### What is your issue of interest (provide sufficient background information)?
The primary need in the current world is LOANS. Banks only receive a large portion of the overall earnings from this. It is advantageous for people to purchase any type of luxury, such as homes, vehicles, etc., as well as for students to manage their educational and living expenditures. However, the decision as to whether the applicant's profile is pertinent for loan approval or not. Banks have a lot of responsibilities.

To make their jobs easier and determine whether the candidate's profile is relevant or not, we will use Machine Learning with Python in this case. This will be done by using important features like applicant income, credit history, applicant income, and marital status.

#### Why is this issue important to you and/or to others?
As everything runs on money these days and every individual is opting for the option of a loan, I feel having accurate information on savings can help in predicting the exact amount of the loan that an individual can bear and also avoid any kind of discrimination.

#### What questions do you have in mind and would like to answer?
Will all the key features(Marital Status, Education, Applicant Income, Credit History, etc.) be sufficient to predict if the candidate's profile is relevant to be eligible for the job? Which model makes the best prediction?

#### Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?
Data source: https://www.kaggle.com/code/hafidhfikri/loan-approval-prediction This dataset contains 614 rows and 13 columns with a file size of 37.1 KB.

This dataset has 13 important features Gender Married Dependents Education Self_Employed ApplicantIncome CoapplicantIncome LoanAmount Loan_Amount_Term Credit_History Property_Area Loan_Status

#### What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?
The unit of Analysis is to use the best model to bring out the predictions on the candidate's eligibility criteria for the loan to get sanctioned( Focusing on the mentioned features).

#### What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?
The target variable will be the Loan_status. I think Univariate Analysis works with this dataset where a frequency table can be used for categorical features and Probability Density Functions(PDF) can be used for the distribution of the numerical variables.

#### What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
Logistic Regression(Using Stratified k-folds Cross-validation)

Random Forest

Decision Tree

XGBoost

#### How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?
The plan of action is to evaluate the models using the evaluation metrices to calculate the accuracy, to derive the ROC curve.

#### What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?
By the time it is done, we have the best model that captures the strategies and predictions needed to address these kinds of challenges. Additionally, it will be evident what each model's function is.

