# Loan_Prediction

Many Student benefit with loans to manage their education and living expenses, and for people to buy any kind of luxury like houses, cars, etc.

We will be using Machine Learning with Python to ease their work and predict whether the candidate’s profile is relevant or not using key features like Marital Status, Education, Applicant Income, Credit History, etc.

## Dataset

| Column Name       | Description                                                |
|-------------------|------------------------------------------------------------|
| Loan              | A unique ID for each loan application                      |
| Gender            | Gender of the applicant  -> Male, Female                   |
| Married           | Marital status of the applicant    ->  Yes, No             |
| Dependents        | Number of dependents the applicant has                     |
| Education         | Educational qualification of the applicant -> Graduated, Not Graduated  |
| Self_Employed     | Indicates whether the applicant is self-employed   -> Yes, No          |
| ApplicantIncome   | Income of the applicant (in currency)                      |
| CoapplicantIncome | Income of the co-applicant (if any)                        |
| LoanAmount        | Amount of loan applied for (in thousands)                  |
| Loan_Amount_Term  | Term of the loan (in months)                               |
| Credit_History    | Credit history of the applicant's repayment of debts  -> 1 - Good credit history, 0 - Poor credit history |
| Property_Area     | Area of property  -> Rural, Urban, Semi-urban              |
| Loan_Status       | Status of the loan application  -> Y - Yes, N - No |



## By following the Steps
1. **Data Cleaning**
   - Handle missing values
   - Remove duplicate entries

2. **Data Transformation**
   - Feature scaling
   - Encoding categorical variables

3. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics
   - Data visualization
   - Correlation analysis

4. **Feature Selection**

5. **Data Splitting** 
    - Data -> Train : Validation : Test -> 70: 10 :20
  
6. **Modeling** -> From characteristics of Target varible it is a classification problem
    - LogisticRegression 
    - RandomForestClassifier
    - SVC  
    - KNeighborsClassifier 
    - DecisionTreeClassifier 
7. **Model Evaluation**
8. **Test Model Evaluation**


