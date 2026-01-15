# multi-family-acquisition-model
I. Methodology and Formula Logic

The model was built from a "blank-sheet" foundation to calculate the investment viability of a 4-unit residential asset.

Gross Potential Rent (GPR): Calculated as Units×Monthly Rent×12. This establishes the maximum theoretical earning capacity of the asset.

Effective Gross Income (EGI): Derived by applying a 5.0% vacancy factor to the GPR. This accounts for economic loss due to tenant turnover and non-payment.

Net Operating Income (NOI): Calculated by subtracting normalized operating expenses (derived from a granular data-cleaning audit) from the EGI. This represents the property's unlevered cash flow.

Annual Debt Service: Calculated using the PMT function in Excel, utilizing a monthly interest rate (6.5%/12) and a 360-month amortization schedule (30 years) against a 75% Loan-to-Value (LTV).

II. Audit Findings & Data Normalization

A critical component of this project was the "Data Janitor" phase, where messy property artifacts were converted into machine-ready data.

Insurance Audit: Identified a 10% discount for upfront premium payments, reducing the annual expense from $3,000 to $2,700.

OpEx vs. CapEx: Identified a one-time roof repair ($1,200). This was correctly categorized as a Capital Expenditure and excluded from the NOI calculation to avoid artificially depressing the property's value.

III. Sensitivity & Risk Analysis

To test the "chaos" of real-world finance, a sensitivity analysis was performed on the Vacancy Rate.

Break-Even Occupancy: The model determined a break-even point of 76.7%. Any occupancy below this level results in negative cash flow after debt service.

Variable Stress Test: The model demonstrated that increasing vacancy from 5% to 15% reduces annual cash flow from $13,171 to $5,971, a 54% decrease in investor profit.
