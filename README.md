Questios asked that my analysis answered were:
What is the average job satisfaction level of employees who left FAU Bank? 
• What is the average salary satisfaction level of employees who left FAU Bank? 
I converted low to 1, medium to 2 and high to 3 by mapping salary 
• For how long have employees who have left, stayed with FAU Bank? 
• Does salary play a role for people who decide to quit their job? 
Yes salary plays a role, as most who left earned low salaries 
• With which attributes is the label column 'left' highly correlated to? Print a correlation 
matrix, and discuss your findings.  
For Employees who left Job satisfaction level is the most significant negative 
correlation. I calculated the Pearson correlation coefficient by data binning by transforming 
continuous data types for Job satisfaction level and last performance evaluation into 
categorical data. pd.cut() function was used to categorize continuous variables into 
discrete intervals 
I created a new feature by multiplying completed projects and average working hours 
monthly. 
# Employee-Turnover-Analytics
