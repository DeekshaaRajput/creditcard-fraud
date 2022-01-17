**PROBLEM STATEMENT**: The goal for the credit card companies is to be able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

**DATASET**: 
i) The dataset is highly imbalanced, the positive class (frauds) account for 0.172% of all transactions.
ii) Dataset contains only numeric input variables which are a result of the PCA transformation. Due to confidentiality issues, the original features and more background information about the dataset has not been provided.
iii) Dataset-  https://www.kaggle.com/mlg-ulb/creditcardfraud?select=creditcard.csv

**PROPOSED APPROACH**:
a. INPUT
	Dataset mentioned before having PCA transformation taken from kaggle.

b. OUTPUT
	An ensemble machine learning model for fraud detection.

c. DATA PREPARATION
Data was highly imbalanced, so under sampling of the majority class was done. 

**MODEL TRAINING**: Model is trained on different model Logistic Regression, Decision Tree, Random Forest and KNN. 

