# Foundation-on-Artificial-Intelligence
# 01_Kelompok_J_2 - I Want to Withdraw All My Savings in Cash!

This Python project simulates a bank system for liquidating customer savings into cash denominations based on the available paper money and coins. The program accepts an integer input representing the customer's savings (between 0 and 1 billion Rupiah), and calculates how many of each denomination are required to fulfill the withdrawal request.

Denominations Available:
| **Paper Money** | **Coin** |
|-----------------|----------|
| Rp 100,000      | Rp 1,000 |
| Rp 50,000       | Rp 500   |
| Rp 20,000       | Rp 200   |
| Rp 10,000       | Rp 100   |
| Rp 5,000        |          |
| Rp 2,000        |          |

Rules:
The program must prioritize issuing the largest denomination first.
If there is a balance that cannot be cashed out (i.e., the remaining amount is less than the smallest denomination), the program will notify that part of the withdrawal cannot be processed.
The bank will calculate the number of paper money and coins required and report the total number of each.
The maximum withdrawal amount is capped at 1 billion Rupiah. If the input exceeds this limit, it will notify the user that the amount is too large.

Input:
An integer representing the amount of savings the customer wants to withdraw. The value must be between 0 and 1 billion Rupiah.

Output:
The program will display:
How many of each denomination are needed (from largest to smallest).
The total count of paper money and coins.
Any remaining amount that cannot be cashed out.

# 01_Kelompok_J_3 - HR Metrics and Analytics

This project involves analyzing an HR-related dataset created for a graduate MSHRM course at New England College of Business. The dataset contains various employee-related metrics, such as performance scores, reasons for termination, and employee demographics. This analysis aims to uncover patterns related to employee termination, performance evaluation, and recruitment sources. The goal is to provide actionable insights for HR professionals to optimize decision-making in employee management.

Tasks:

Data Aggregation:
Answer multiple aggregation questions using Pandas. The detailed questions are available in the provided .ipynb file. These questions help uncover key insights from the dataset.
Exploratory Data Analysis (EDA):

Perform EDA on the target variable (employee termination) to analyze which feature variables are related to employee termination, such as:
- Most common reasons for termination
- Termination by department
- Termination by gender
Create a minimum of five visualizations to illustrate the insights discovered during the EDA process.

Key Analysis Questions:

a. Is there any relationship between an employee’s manager and their performance score?

b. What are the best recruiting sources to ensure a low employee termination ratio?

Goals:

- To provide insights on employee retention and performance.

- To assist HR professionals in making data-driven decisions regarding employee management, performance evaluations, and recruitment strategies.
