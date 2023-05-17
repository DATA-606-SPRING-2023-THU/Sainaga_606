## PROJECT OVERVIEW

#### Today, many banks only approve loans after lengthy validation and verification processes.However, there is no assurance that the selected customer is safe. Thus, it is imperative to employ a number of strategies in the banking sector to select clients who make loan payments on time. The objective of this project is to predict loan approval or denial based on information about applicant income, credit history, gender, and the number of dependents. So, my aim is to extract the best model that helps in predicting the loan status of an applicant from the corresponding accuracy scores. 

## PLAN OF ACTION

#### As the cleaned works best for the further development, the initial step is Exploratory Data Analysis. This includes
##### 1. Checking for the duplicate values(The dataset does not have any duplicate values)
##### 2. Checking for the null values(This dataset had few null values which are replaced by the mean and mode of their columns. 
##### 3. Coverting the categorical values to the numerical variables using Label Encoder( As most of the important featurs are in object datatype(Categorical Variables) and had to convert it to the numerical variable to bring out the prediction on the loan approval.

## INSIGHTS FROM THE VISUALIZATION

#### Around 70% of the Applicants has a clear chance of loan approval
#### About 80% of Applicants are male and married. 
#### Fair chance of loan approval is more towards the graduates and self employed.
#### Semi urban area residents has more chance for the approval
#### Frequency distribution for the numerical variable(Applicant Income and CoApplicant Income and checking the affect of this distribution on the Loan Status) and the applicant income is normally distributed.

## MODEL BUILDING

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
#### Random Forest       : 0.788618
#### Decision Tree       : 0.699187
#### Naive Bayes         : 0.829268
#### XG Boost            : 0.772358
#### KNN                 : 0.650407
#### SVM                 : 0.837398

#### From the accuracies of each model, it can be inferred that Logistic Regression and SVM worked best with 83.9% of accuracy.

## CONCLUSION

#### The features of dataset with all the information including from the gender to the credit history been a helping hand in extracting the accurate information in analysis if an applicant is eligible to fulfill the needs( Housing, Electronics, Education etc.,) also played a major role in extracting the useful insights.








