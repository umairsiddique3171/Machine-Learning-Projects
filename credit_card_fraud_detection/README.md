# credit_card_fraud_detection
This repository contains the source code of the project focused on training different Machine Learning models using GridSearchCV for credit card fraud detection (i.e classifying transactions as legit or fraudulent). Several Preprocessing techniques were applied to the data such as EDA, normalization, data sampling, etc.  
<br>
Data for this project can be found here : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
<br>
Dataset Description: 
<br>
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
<br>
Author : Umair Siddique
