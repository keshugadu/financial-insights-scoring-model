# financial-insights-scoring-model
A scoring model created to analyze the financial behavior of a family based on a dataset tracking the family's income, savings, credit card expenditure, loan payments and financial goals
# Setup Instructions
Install necessary Python packages and libraries such as Numpy, Pandas, Matplotlib, Seaborn and Plotly
Install Jupyter Notebook for a proper working environment

# Model Logic
1. Savings-to-Income Ratio (25%)
   - A higher ratio indicates good financial planning and ability to save.
   - If Savings/Income ≥ 0.5: Full score for this factor. Gradual decrease for lower ratios

2. Monthly Expenses as a Percentage of Income (20%)
   - Lower expenses relative to income indicate better financial control.
   - If Expenses/Income ≤ 0.5: Full score for this factor. Gradual decrease for higher percentages

3. Loan Payments as a Percentage of Income (15%)
   - High debt repayment indicates financial strain.
   - If Loan Payments/Income ≤ 0.2: Full score. Penalize higher percentages.

4. Credit Card Spending Trends (15%)
   - Excessive use may indicate poor financial discipline.
   - If Credit Card Spending ≤ 20% of total expenses: Full score. Gradual reduction for higher proportions.

5. Financial Goals Met (%) (10%)
   - Meeting financial goals reflects good planning and execution.
   - Directly proportional
