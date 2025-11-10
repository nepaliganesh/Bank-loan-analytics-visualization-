# Bank-loan-analytics-visualization-
interactive dashboard for analyzing and monitoring bank loan applications — includes loan status trends, approval rates, and customer insights built with Excel
There is dataset file

[dataset for bank loan application.xlsx](https://github.com/user-attachments/files/22458248/dataset.for.bank.loan.application.xlsx)
Key Columns:

Id, Member_Id → Unique identifiers for each loan and borrower.

Address_State → Applicant’s state of residence (useful for regional analysis).

Application_Type → Indicates if the application is individual or joint.

Emp_Length, Emp_Title → Employment details used to assess job stability.

Grade, Sub_Grade → Lending club–style credit grading of applicants.

Home_Ownership → Ownership type (Own, Rent, Mortgage).

Issue_Date, Last_Payment_Date, Next_Payment_Date → Time-based loan details for tracking repayment.

Loan_Status → The outcome/status (e.g., Fully Paid, Charged Off, Current).

Verification_Status → Whether income or identity has been verified.

Annual_Income, Dti (Debt-to-Income ratio), Installment, Int_Rate, Loan_Amount, Total_Payment, Total_Acc → Numeric and financial indicators used for analysis and performance comparison.

Good vs Bad Loan Sheet

Purpose:
An enhanced version of the Data sheet, with one extra column, “Good vs Bad Loan”.

Added Column:

Good vs Bad Loan: A derived field likely created using the “Loan_Status.”

“Good Loan” = Fully Paid or Current

“Bad Loan” = Charged Off, Default, or Late

Pivot Table 1

Purpose:
The first pivot table sheet summarizes part of data, comparing loan grades or status distribution.

Grade or Loan Status vs Count of Loans / Average Interest Rate / Total Loan Amount.

Pivot Table 2
comparing loan type or home ownership against default rates or income averages.

Pivot Table 3
Loan purpose vs Average Interest Rate
Loan amount distribution
Income group performance

Pivot Table 4
indicating a comprehensive summary, by state .

Dashboard Sheet
<img width="723" height="577" alt="image" src="https://github.com/user-attachments/assets/7153d514-586e-4646-a072-0609cd42a3cf" />


Purpose:
Percentage of good vs bad loans
Average interest rate by grade
Loan distribution by state or purpose
Total payment vs loan amount comparisons
