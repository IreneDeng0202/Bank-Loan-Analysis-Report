# Bank Loan Reporting Dashboard

## Project Overview
This Power BI report delivers an in-depth analysis of bank loan operations, enabling key stakeholders such as financial analysts and banking executives to make informed decisions. The report is structured into three key sections: Summary, Overview, and Details, each offering a distinct analytical perspective on loan applications, disbursement, repayment trends, and portfolio performance

## Key Features
- **Summary Page ：Executive Loan Portfolio Insights**:This high-level dashboard presents a holistic view of the bank’s loan performance, allowing leadership to monitor key performance indicators (KPIs) at a glance:
Annual Metrics: Total loan applications, total funded amount, and total amount received.
Month-to-Date (MTD) Insights: MTD loan applications, funded amount, and received amount.
MoM (Month-over-Month) Trend Analysis: Comparative trends in loan volume, disbursement, and repayments.
Risk & Profitability Indicators: Average interest rate and Debt-to-Income (DTI) ratio.
Loan Status Breakdown: Analysis of fully paid, charged-off, and current loans to assess portfolio health.
Dynamic Filtering: Integrated slicers enable real-time analysis by loan purpose, loan grade, and state, allowing decision-makers to refine insights based on specific business criteria.
- **Overview Page**: Visualizes total loan applications trends over time, distribution by state, and breakdown by loan purpose and term, by employee lenth, by purpose, by home ownership； 这些 total loan application 根据我pbi field paramether , 可以换成total funded amount ; total amounted receiev;查看以上三个指标的byXX 情况；
- **Details Page**: Provides a deep dive into top 10  individual loan records, highlighting key information  for each individual,

## Key Metrics Calculated
- **Total Loan Applications**
- **Good vs. Bad Loan Amounts**
- **Average Interest Rate and DTI** (Debt to Income ratio)

## How to Use
1. **Download the PBIX file**: Open with Power BI Desktop.
2. **Review SQL Scripts**: Check the SQL scripts for how data is extracted and prepared.
3. **Study DAX Calculations**: Refer to the included DAX expressions document to understand the calculations behind the metrics.

## Data Source and Preparation
Data is sourced from the bank's operational databases and processed using SQL Server for initial extraction and transformation. Further data modeling and calculations are performed in Power BI using DAX.

## Repository Contents
- `BankLoanReport.pbix` - Main Power BI file containing the report.
- `SQL_Scripts.sql` - Scripts used for data extraction.
- `DAX_Expressions.txt` - Documentation of all DAX expressions used in the report.
- `Data_Model_Description.md` - Detailed description of the data model and sources.

## Contributing
Feel free to fork this project and adapt the reports to your needs. Contributions to enhance the dashboard or extend its capabilities are welcome.

