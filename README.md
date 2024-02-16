### Project Link : [Supervised Machine Learning](https://github.com/PinkyBhansali/Machine-Learning/tree/master/ML-%20Classification%20Problem/ATM%20Fraud%20Prediction)

### Problem Statement: 
PredCatch Analytics' Australian banking client's profitability and reputation are being hit by fraudulent ATM transactions. They want PredCatch to help them in reducing and if possible completely eliminating such fraudulent transactions. PredCatch believes it can do the same by building a predictive model to catch such fraudulent transactions in real time and decline them

### Objective: 
The objective is to build fraud detection & prevention predictive model in the first step. If successful, in the 2nd step we will have to present your solutions and explain how it works to the client. The data has been made available to you.

### Imbalance Dataset: 
We have imbalance dataset with fraud transactions of around 0.17% and valid transactions of 99.83%. So as this is critical dataset and important part of model building we used both approaches to build the model:
1) Balance the data and perform model building (using SMOTE technique)
2) model building without balancing data(using Anomaly detection - Isolation Forest model and Local Outlier Factor specially designed algo for these kind of data)

### Models used for training 
-	Logistic Regression, Decision Tree, Random forest, XGBClassifier, GaussianNB, GradientBoosting Classifier, Stacking Classifier
- Out of all the models Gradient Boosting is  performing better with accuracy of 98%  and recall score of 99 on valid transaction and 97 on fraud transaction. Even the F1 score is 98 % for both the classes. 

              precision    recall  f1-score   support

         0.0       0.97      0.99      0.98     56824
         1.0       0.99      0.97      0.98     56902

        accuracy                           0.98    113726
        macro avg       0.98      0.98      0.98    113726
        weighted avg       0.98      0.98      0.98    113726
