# Hello there, fintech enthusiasts! 👋💰

Welcome to **Loan Repayment Regression Project**. This project uses Sequential Neural Networks to predict loan repayment.

## What's it all about? 🤔

This project deals with the LendingClub dataset with some additional features to give better insights. LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

The goal is to build a model that can predict whether or not a borrower will pay back their loan based on historical data on loans given out and information on whether or not the borrower defaulted (charge-off). The "loan_status" column contains the label; it is the dependent variable (predicting class).

## 📝 Business Understanding
You work for the LendingClub company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for takin actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
* Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
* Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
* Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
  
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## 🎯 Business Objectives

* LendingClub is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
* Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who defaultcause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
* If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA and machine learning is the aim of this case study.
* In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.
* To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

## How does it work? 🛠️

### Steps Performed:

1. **Exploratory Data Analysis** - We perform Exploratory Data Analysis using Python's NumPy, pandas, Seaborn, and Matplotlib modules.

2. **Data Preprocessing and Feature Engineering** - We perform Data Preprocessing and Feature Engineering to remove features which do not impact our goal prediction.

3. **Model Building and Training** - We perform Model Building and Training. It involves building a Sequential Neural Network using Keras for Loan Repayment Prediction. Early Stopping mechanism has been employed.

4. **Evaluation of Model Performance** - We perform Evaluation of Model Performance using classification report and confusion matrix.

## Outcome 🎯

We achieve an accuracy of 89%. Finally, we have configured Tensorboard with Jupyter notebook to view the essential model graphs for model evaluation and the workflow.

## Contributing 🤝

Please contribute using [GitHub Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request.

## Support 🙌

If you like what you see, give us a star ⭐. Thanks and happy coding! 🚀



