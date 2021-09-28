# Loan Repayment Regression Project
## About the Dataset:
* This project deals with the LendingClub dataset with some additional features to give better insights.
* LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

## Goal:
* Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), we want to build a model that can predict wether or not a borrower will pay back their loan.
* The "loan_status" column contains the label ; it is the dependent variable(predicting class).

## Steps Performed:
* Step I -  We perform Exploratory Data Analysis using Python's NumPy,pandas,Seaborn and Matplotlib modules.
* Step II -  We perform Data Preprocessing and Feature Engineering to remove features which do not impact our goal prediction. 
* Step III -  We perform Model Building and Training. It involves building a Sequential Neural Network using Keras for Loan Repayment Prediction. Early Stopping mechanism has been employed.
* Step IV - We perform Evaluation of Model Performance using classification report and confusion matrix.

## Outcome:
We achieve an accuracy of 89%. Finally, I have configured Tensorboard with Jupyter notebook to view the essential model graphs for model evaluation and the workflow.


