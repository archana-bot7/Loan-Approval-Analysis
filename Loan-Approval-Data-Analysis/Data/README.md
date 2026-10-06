# Data

The supplied report analyzes **614 applications** with **13 fields**.

The original raw dataset was not supplied separately, so no CSV has been fabricated.

## Cleaning documented in the report
- 149 missing cells across 7 columns were handled column-by-column.
- Missing Credit_History retained as **Not Available**.
- LoanAmount filled with median **128 thousand**.
- Self_Employed → **No**; Dependents → **0**; Loan_Amount_Term → **360 months**.
- Gender → **Not Stated**; Married → **Yes** for missing values.
- No duplicate applications and no rows removed.
- Loan_Status recoded to Approved/Rejected.
- Credit_History recoded to Good/Poor.
- Total_Income and grouped income/loan bands were added.
