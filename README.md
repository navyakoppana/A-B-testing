# A/B-testing
## Table of Contents
1. Project description
2. Libraries used
3. Files used
4. Summary of analysis

### Project description
This project underlies the concepts of Probability,Hypothesis testing,logistic regression approach to decide whether a new webpage or an old webpage should be kept by an e-commerce website in order to increase the number of users who decide to pay for company's product.

### Libraries used
1. Numpy
2. Pandas
3. Matplotlib
4. Statsmodels.api
5. Logistic Regression model(Logit)

### Files used
1. ab_data.csv
2. countries.csv
3. README.md
4. Analyze_ab_test_results_notebook.ipynb

### Summary of analysis
1. The number of customers in the control and treatment groups are nearly equal, 12% of control group customer have been converted and 11.88% of treatment group have converted, so the new treatment group users have slightly higher conversions than that old control group users.
2. The value of z_score i.e., 1.310 lies within the 95% confidence intervals of +/- 1.960 and p_value i.e., 0.905 is greater than 0.05, which clearly states that we fail to reject null hypothesis i.e.,converted probability (or rate) for the old and new pages are equal is not true.
3. The same analysis is carried out by regression approach which initially was done using hypothesis testing and the outcome is the same as previous one.
4. Based on all the tests performed like actual difference computed,Z-test,logistic regression model we conclude that new page has equal chance of converting users as that of old page since all the cases have failed to reject null hypothesis.So investing in old page saves time and money.
