## DATA_606_CAPSTONE PROJECT

#### Professor: Dr. Chaojie Wang
#### Student: Sai Naga Venkata Santoshi Nitya Bandaru
#### Semester: Spring 2023
#### Campus ID: PX70339

## PROJECT TITLE: LOAN PREDICTION ANALYSIS




## PROJECT OVERVIEW:

#### Today, many banks only approve loans after lengthy validation and verification processes.However, there is no assurance that the selected customer is safe. Thus, it is imperative to employ a number of strategies in the banking sector to select clients who make loan payments on time. The objective of this project is to predict loan approval or denial based on information about applicant income, credit history, gender, and the number of dependents. So, my aim is to extract the best model that helps in predicting the loan status of an applicant from the corresponding accuracy scores. 


## PROBLEM STATEMENT:

#### The problem statement for this project is to predict the loan status of the applicant by verifying their details while they fill out the application form. The aim is to effectively use the Machine Learning models in predicting the accurate status of the loan( Yes/No) and to check which model works the best. 


## PLAN OF ACTION:

#### As the cleaned works best for the further development, the initial step is Exploratory Data Analysis. This includes
##### 1. Checking for the duplicate values(The dataset does not have any duplicate values)
##### 2. Checking for the null values(This dataset had few null values which are replaced by the mean and mode of their columns. 
##### 3. Coverting the categorical values to the numerical variables using Label Encoder( As most of the important featurs are in object datatype(Categorical Variables) and had to convert it to the numerical variable to bring out the prediction on the loan approval.

## TECHNOLOGIES USED:

#### Programming Language: Python
#### Libraries used: Pandas, Seaborn, Sklearn, Matplotlib
#### Techniques: Machine Learning Models

## DATASET:

#### Data source: https://www.kaggle.com/code/hafidhfikri/loan-approval-prediction This dataset contains 614 rows and 13 columns with a file size of 37.1 KB.

#### This dataset has 13 important features Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status



## INSIGHTS FROM THE VISUALIZATION:

#### Around 70% of the Applicants has a clear chance of loan approval
#### About 80% of Applicants are male and married. 
#### Fair chance of loan approval is more towards the graduates and self employed.
#### Semi urban area residents has more chance for the approval
#### Frequency distribution for the numerical variable(Applicant Income and CoApplicant Income and checking the affect of this distribution on the Loan Status) and the applicant income is normally distributed.

![Image 5-18-23 at 9 06 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/75921284-d84e-4be8-aa7b-8a4dfeb17d38)
![image](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/b232b5b4-580a-462a-a200-5bc66a9c622e)
![Image 5-18-23 at 9 14 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/9c9cce53-c904-4318-b58b-37f863b9e135)
![Image 5-18-23 at 9 16 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/13e2eaf5-46b5-444c-9dd8-222bcf0b13e3)
![Image 5-18-23 at 9 17 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/0fa0d3bb-ef34-4dc9-858b-ae9b8366b78a)








## MODEL BUILDING:


#### The model building included splitting the data into train and test.
#### The models I have used are: 
#### Logistic Regression
#### Random Forest
#### Decision Tree
#### Naive Bayes
#### XG Boost
#### KNN
#### SVM

#### Target Variable: Loan_Status

#### The accuracies of each model are:

#### Logistic Regression : 0.837398
![Image 5-18-23 at 9 22 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/c60ddadf-2bfb-48b7-bb75-443354df79c1)

#### Random Forest       : 0.788618
![Image 5-18-23 at 9 32 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/cb7ca234-94d8-4543-8f71-eeaa0a341a40)

#### Decision Tree       : 0.699187
![Image 5-18-23 at 9 29 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/41388e54-94d8-4781-86ee-16f40b3df892)

### Naive Bayes         : 0.829268
![Image 5-18-23 at 9 28 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/7adb4cd0-c504-406d-aec1-4912d0401d5f)

#### XG Boost            : 0.772358
![Image 5-18-23 at 9 30 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/f0a9ef85-1297-4ef6-9d9a-4a9e35604937)

#### KNN                 : 0.650407
![Image 5-18-23 at 9 24 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/ea45a95d-0634-4248-9446-66d25c715275)

#### SVM                 : 0.837398
![Image 5-18-23 at 9 27 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/0e57e592-6e59-4dbc-a41f-1e68f042b2ef)



#### From the accuracies of each model, it can be inferred that Logistic Regression and SVM worked best with 83.9% of accuracy.
![Image 5-18-23 at 9 19 PM](https://github.com/SaiNagaBandaru/Sainaga_606/assets/124278675/915e0619-ba79-4fd3-9c18-9fbd184aad79)


## CONCLUSION

#### The features of dataset with all the information including from the gender to the credit history been a helping hand in extracting the accurate information in analysis if an applicant is eligible to fulfill the needs( Housing, Electronics, Education etc.,) also played a major role in extracting the useful insights.

## REFERENCE:

#### https://github.com/SaiNagaBandaru/Sainaga_606
#### https://medium.com/mlearning-ai/univariate-bivariate-and-multivariate-data-analysis-in-python-341493c3d173
#### https://realpython.com/logistic-regression-python/
#### www.analyticsvidhya.com


## LINKS: 

[Capstone Presentation_PX70339 (1).pptx](https://github.com/SaiNagaBandaru/Sainaga_606/files/11512754/Capstone.Presentation_PX70339.1.pptx)

https://www.youtube.com/channel/UCaFgCPlzuv1v1LeXqYAax6Q





