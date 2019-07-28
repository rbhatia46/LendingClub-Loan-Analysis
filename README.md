# LendingClub-Loan-Analysis

![Logo](https://d1ic4altzx8ueg.cloudfront.net/niche-builder/5cb94cef96518.png)

Lending loans to ‘risky’ applicants is the largest source of financial loss(called credit loss) for any bank/lending company. If we are able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using Data Analysis is the aim of this case study. Lending Club (a peer-to-peer lending company) wants to understand the driving factors behind loan default. The company can utilise this knowledge for its portfolio and risk assessment.
2 types of risks are associated with the
bank’s decision:
* If the applicant is likely to repay the loan, then not approving the
loan results in a loss of business to the company

* If the applicant is not likely to repay the loan, i.e. he/she is likely to
default, then approving the loan may lead to a financial loss for the
company

## Data Used :
The data used was acquired from Kaggle, open-sourced by LendingClub itself to welcome Data Scientist help them identify driving factors behind 
loan default, using historic data of loan applications.

* The data given contains the information about past loan applicants and
whether they ‘defaulted’ or not. The aim is to identify patterns which
indicate if a person is likely to default, which may be used for taking
actions such as denying the loan, reducing the amount of loan, lending (to
risky applicants) at a higher interest rate, etc.

* When a person applies for a loan, there are 2 types of decisions that
could be taken by the company:
  * **Loan accepted** - 
  If the company approves the loan, there are 3
possible scenarios described below:
  1. Fully paid: Applicant has fully paid the loan (the principal and
the interest rate)
  2. Current: Applicant is in the process of paying the installments,
i.e. the tenure of the loan is not yet completed. These
candidates are not labelled as 'defaulted'.
  3. Charged-off: Applicant has not paid the instalments in due
time for a long period of time, i.e. he/she has defaulted on the
loan.

  * **Loan rejected** - The company had rejected the loan (because the
candidate does not meet their requirements etc.). Since the loan was
rejected, there is no transactional history of those applicants with the
company and so this data is not available with the company (and thus
in this dataset)

* This project is typical a Data Exploration project and tries to find as much findings as possible without the use of any Machine Learning and just simple plain EDA and Data Visualization.
* The analysis and Visualizations in the notebook are self-explanatory to decide the driving factors for a new loan application and act accordingly.
