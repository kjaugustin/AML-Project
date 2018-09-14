# AML-Project

# Credit Card Fraud Detection


Credit card fraud detection is a challenging classification problem. Though fradulent transactions are few compared to legit transactions, they represent major losses for financial institutions. So machine learning models for credit card fraud detection should maximize the recall score and minimize the false negatives. Traditional machine learning algorithms such as linear regession, SVC, LDA, Random Forest, Decision Tree etc can be used to build machine learning models to classify fradulent transactions, however they may not very effectively reduce the false negatives. The false negative rate for the best model built using the traditional machine learning algorithms scored around 10%. Here we show a modification of the machine learning algorithm that reduced the false negative rate from 10% to 2%. 

## Dataset

The dataset used for this Machine Learning project is obained from Kaggle. A detailed description about the data set could be found at https://www.kaggle.com/agpickersgill/credit-card-fraud-detection/data .

The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on http://mlg.ulb.ac.be/BruFence and http://mlg.ulb.ac.be/ARTML.

The dataset contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the dataset does not provide the original features or the background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA. The only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, which can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
