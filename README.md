# Credit Fraud
### Context
It is important that credit card companies can recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
### Content
<p>The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.</p>
<p>It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.</p>
<p>Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification. </p>

### Section 1: Explorartory Data Analysis (EDA)
- In this section talk about your data, patterns, trends and or issues with the data. 
### Section 2: Data Processing 
- Talk about how you transformed the data. This is where you talk about missing data, outliers, creation of new features and more. Be sure to explain why you used a certain technique. 
### Section 3: Model Developement
1. Model Selection
2. Model Development process 
3. Model Result
4. Repeat steps 2 and 3 for each model you create. 
Please be sure to elaborate why you used a certain model. 
### Section 4: Model Comparison
1. Conclusion
2. Future steps : Given time contrainst, compute power and other resources what additional techniques and tools do you believe could advance performance of the model. Please describe why you think it might help. 
