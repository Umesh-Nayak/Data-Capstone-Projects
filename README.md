# Banking - Vehicle Dafaulter Analysis

Banking.
Course-end Project 2
Description

Data Analysis is the process of creating a story using the data for easy and effective communications. It utilizes visualization methods such as plots, charts, and tables to convey what the data holds beyond the formal modeling or hypothesis testing task.

 

Read the information given below and also refer to the data dictionary provided separately in an excel file to build your understanding.

 

Problem Statement

 

Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and an increase in vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default.

There is one dataset with data that has 41 attributes.

You are required to determine and examine factors that affect the ratio of vehicle loan defaulters. Also, use the findings to create a model to predict the potential defaulters.

 

Approach:

1. Data Preliminary Analysis:

Perform preliminary data inspection and report the findings like the structure of the data, missing values, duplicates, etc.
Variable names in the data may not be in accordance with the identifier naming in Python. Change the variable names accordingly.
The presented data might also contain missing values, therefore, exploration will also lead to devising strategies to fill in the missing values. Devise strategies while exploring the data.
 

2. Performing EDA:

Provide the statistical description of the quantitative data variables
How is the target variable distributed overall?
Study the distribution of the target variable across the various categories like branch, city, state, branch, supplier, manufacturer, etc.
What are the different employment types given in the data? Can a strategy be developed to fill in the missing values (if any)?  Use pie charts to express how different types of employment defines defaulter and non-defaulters.
Has age got something to do with defaulting? What is the distribution of age w.r.t. to defaulters and non-defaulters?
What type of ID is presented by most of the customers as proofs?
Explain the factors in the data that may have an effect on ratings e.g. No. of cuisines, cost, delivery option, etc.
 

 

3. What type of ID was presented by most of the customers as proofs?

4. Performing EDA and Modeling:

Study the credit bureau score distribution. How is the distribution for defaulters vs. non-defaulters? Explore in detail.
Explore the primary and secondary account details. Is the information in some way related to the loan default probability?
Is there a difference between the sanctioned and disbursed amount of primary and secondary loans? Study the difference by providing appropriate statistics and graphs.
Do customers who make higher numbers of inquiries end up being higher risk candidates?
Is credit history, that is, new loans in the last six months, loans defaulted in the last six months, time since the first loan, etc., a significant factor in estimating the probability of loan defaulters?
Perform logistic regression modeling, predict the outcome for the test data, and validate the results using the confusion matrix.
