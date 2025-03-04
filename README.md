# Bank Loan Reporting Dashboard

## 1.Project Overview
This Power BI report delivers an in-depth analysis of bank loan operations, enabling key stakeholders such as financial analysts and banking executives to make decisions. The report is structured into three key sections: Summary, Overview, and Details, with each offering a distinct analytical perspective on loan applications, disbursement, repayment trends, and portfolio performance.

## 2.Key Features
## 2.1 Summary Page Executive Loan Portfolio Insights
This dashboard analyzes Loan Applications, Total Funded Amount, Total Amount Received, Average Interest Rate, and Average DTI from multiple perspectives to track performance and trends:
- **Annual Metrics**: Aggregates yearly totals to assess overall loan volume and financial impact.
MTD (Month-to-Date) Insights: Monitors current month activity to track ongoing performance.
MoM (Month-over-Month) Trends: Compares monthly fluctuations to identify emerging patterns and growth trends.
Loan Status Breakdown: Evaluates these metrics across different loan statuses (Fully Paid, Charged-Off, and Current) to assess portfolio health.
Dynamic Filtering: Enables real-time analysis by Loan Purpose, Loan Grade, and State, providing targeted insights for strategic decision-making.
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

