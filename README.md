# Assessing-Credit-Risk-with-Machine-Learning

**Problem: **
The bank requires an optimized system for its prospective customer loan approval process by predicting their credit risk based on the given German Credit Dataset.

We used a data-backed machine learning approach that identifies where the customer has good (1) or bad (0) creditworthiness so the bank can increase profitable lending while decreasing the risk of defaults.

The dataset includes 1000 records and 20 customer attributes (such as account balance, credit history, employment duration, etc.) along with a target variable — Creditability — that indicates a customer’s credit risk


**Solution: **
We used Weka and Python to implement 2 popular machine learning techniques (Decision Tree and Naïve Bayes)
Each technique had 2 method of experimental implementation: baseline v.s. selected features. Our aim was to compare these 4 models based on accuracy and recall metrics. 

Key Results
Decision Tree Accuracy: 72.35 % baseline vs 72.94% (selected feature)
Naive Bayes Accuracy: 73.82% (selected features) vs 75% baseline
Critical Recall: 93.72% (identifies 94% of creditworthy applicants)
Most Relevant Predictors: Account Balance, Credit Duration, Payment History
