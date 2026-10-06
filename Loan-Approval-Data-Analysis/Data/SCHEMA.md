# Data Schema

| Field | Description |
|---|---|
| Loan_ID | Unique application reference |
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Graduate / Not Graduate |
| Self_Employed | Self-employment status |
| ApplicantIncome | Applicant monthly income |
| CoapplicantIncome | Co-applicant monthly income |
| LoanAmount | Requested loan amount, in thousands |
| Loan_Amount_Term | Repayment term in months |
| Credit_History | Repayment record indicator |
| Property_Area | Rural / Semiurban / Urban |
| Loan_Status | Approved / Rejected |

## Derived fields
- Total_Income
- Grouped income bands
- Grouped loan bands
- Cleaned display versions of Loan_Status and Credit_History
