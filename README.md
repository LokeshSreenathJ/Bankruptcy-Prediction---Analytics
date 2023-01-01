# Bankruptcy-Prediction---Analytics
Built XGBoost Classifier using SMOTE technique and Hyper-Parameter Tuning. Mode of Estimation is "AUC Score" for Binary Classification.

Initially, Built a Logistic Regression model which has given a poor AUC score of 0.52.

Later, Removed the multicollinearity features with in the dataset using pearson's correlation method by choosing threshold as 0.9. Now again modeled the Logistic Regression using the new dataset and the AUC score raised to 0.60.

Then, Using SMOTE (Synthetic Minority OverSampling Technique) created the eqaul observation of the both the classes and then built a new Logistic Regression mode and got the AUC score of 0.62.

Using Non-Parametric approach, built a KNN Classifer using the newer dataset. KNN suffers with the "curse of dimenionality" if n/p ratio is lower. Tuning the hyper-paramerts yielded a modek with AUC score of 0.82.

Finally, most buzzing and trendy XGBoost Classifer was built using SMOTE dataset as Regularization is inherent property of XGBoost. Tuned the hyper-parameters and the resulted in AUC test score of 0.96.

This explains the superiority of Boosting Algorithms.
