# Foundation-on-Artificial-Intelligence
# 01_Kelompok_J_2 - I Want to Withdraw All My Savings in Cash!
Overview
This Python project simulates a bank system for liquidating customer savings into cash denominations based on the available paper money and coins. The program accepts an integer input representing the customer's savings (between 0 and 1 billion Rupiah), and calculates how many of each denomination are required to fulfill the withdrawal request.

Denominations Available:
Paper Money:

Rp 100,000
Rp 50,000
Rp 20,000
Rp 10,000
Rp 5,000
Rp 2,000
Coins:

Rp 1,000 (treated as coins)
Rp 500
Rp 200
Rp 100
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
