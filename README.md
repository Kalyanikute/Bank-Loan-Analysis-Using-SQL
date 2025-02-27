# Bank-Loan-Analysis-Using-SQL
Bank Loan Analysis using Sql 

📌 Bank Loan Analysis Using SQL
Domain: Finance | Technology: SQL

📖 Project Overview
This project analyzes bank loan data using SQL to extract insights on loan applications, funded amounts, repayments, interest rates, and loan statuses. The analysis helps in understanding loan trends and assessing risks in lending.

🔍 Key SQL Queries & Analysis
📊 Loan Applications
Total Loan Applications: COUNT(id)
Monthly Applications (MTD, PMTD): WHERE MONTH(issue_date) = X
💰 Funded & Received Amount
Total Funded Amount: SUM(loan_amount)
Total Amount Received: SUM(total_payment)
📉 Interest Rate & Debt-to-Income (DTI)
Average Interest Rate: AVG(int_rate) * 100
Average DTI: AVG(dti) * 100
✅ Good Loans vs. ❌ Bad Loans
Good Loans (% and Total): loan_status = 'Fully Paid' OR 'Current'
Bad Loans (% and Total): loan_status = 'Charged Off'
🔄 Loan Status Breakdown
Loan distribution based on status, state, term, employment length, home ownership, and purpose
🛠 SQL Techniques Used
✅ Aggregate Functions: SUM(), AVG(), COUNT()
✅ Conditional Filtering: WHERE, CASE WHEN
✅ Grouping & Sorting: GROUP BY, ORDER BY
✅ Monthly Trends: MONTH(issue_date)

📂 Dataset
The dataset includes loan amount, issue date, status, interest rates, borrower details, and repayment history.
