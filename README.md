# fraud-detection

1) Data cleaning including missing values, outliers and multi-collinearity.
A- Dataset contains no missing values, Dataset have high multicollinearity and Selected features have not much outliers.

2) How did you select variables to be included in the model?
A- Removing unneccesary columns such as ('step','nameOrig', 'nameDest') from the dataset because it doesnot affect the target and dropping columns causing  multicollinearity because it will affect the accuracy of the model,the data has no duplicate and null values so nothing to done there and applying SMOTE technique on target column for handling imabalanced dataset.

3) Demonstrate the performance of the model by using best set of tools.
A- For classification problems such as this the evaluation metric are accuracy, precision, recall, f1_score and confusion matrix, auc-roc value which are 
calculated and demonstrate the overall performance of the model.

4) What are the key factors that predict fraudulent customer? and 
5) Do these factors make sense? If yes, How? If not, How not? 
A-'type', 'amount' are most important key factors which predict the fraudulent customer.

 Decision tree classifire gives best accuracy, precision and auroc value
