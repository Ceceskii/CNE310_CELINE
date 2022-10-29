# PYTHON ASSIGNMENT 
## Write a function howManyMonths(start, rate, spending, target) where:

start - the starting balance in your bank account (float)

rate - the monthly interest rate (float) - like 0.001 for 0.1%

spending - the monthly amount that is spent each month (float)

target - the target savings that you’d like to achieve

The function returns how many months it takes to save the target savings amount. The function should return a -1 if the balance goes below 0 because the spending is too high. The function should also return -1 if the target is not reached after 100 months.

Each month you earn the monthly rate of interest, but you also spend the spending amount.

So, next_month_balance = start_balance * (1 + rate) - spending