# Credit-Card-Fraud-Detection


**Business Problem Overview**

For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

In the banking industry, credit card fraud detection using machine learning is not just a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees, and denials of legitimate transactions.

**Understanding and Defining Fraud**

Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the authorized person for financial gain.

The different ways of fraudulent activities are:

• Manipulation/alteration of genuine cards

• Creation of counterfeit cards

• Stolen/lost credit cards

• Fraudulent telemarketing

• Skimming

**Data Source**

Kaggle: [https://www.kaggle.com/mlg-ulb/creditcardfraud](https://www.kaggle.com/mlg-ulb/creditcardfraud)

**Data Dictionary**

Out of a total of 2,84,807 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions.

**Project Pipeline Steps**

• Data Understanding

• Exploratory data analytics (EDA)

• Splitting the data into train &amp; test data

• Model Building with Imbalance data set

- KNN

- Decision Tree

- Random Forest

- XGBoost

• Balancing the data

- SMOTE: it is one type of oversampling but in this we will make the synthetic example of Minority data and will give as a balanced data.

• Model Building with Balance data set

- KNN

- Decision Tree

- Random Forest

- XGBoost

• Model-Building/Hyperparameter Tuning

• Model Evaluation

• Conclusion

**Cost-Benefit Analysis**

The final model will help to find out the best evaluation score and how much fund has been saved.

From the confusion matrix we can evaluate total fraud predictions value (true positive + false positive), correct predictions, incorrect predictions.
