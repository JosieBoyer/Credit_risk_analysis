## Supervised-Learning
## Purpose
Credit risk is an inherently unbalanced classification problem, as there are many more good loans than bad. To test machine learning model accuracy on credit-risk I used 6 different methods.

First, I oversampled the data using the RandomOverSampler and SMOTE algorithms. Second, I undersampled the data using the ClusterCentroids algorithm. Then, I used a combination approach of over and undersampling using the SMOTEENN algorithm. Finally, I tested and compared two new machine learning models that reduce bias,BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk

## Results

![](https://github.com/JosieBoyer/Credit_risk_analysis/blob/main/NRO.PNG) had a balanced score of 65.7%

![](https://github.com/JosieBoyer/Credit_risk_analysis/blob/main/SMOTE.PNG) had a balanced score of 65.3%

![](https://github.com/JosieBoyer/Credit_risk_analysis/blob/main/undersample.PNG) ClusterCentroids had a balanced score of 65.3%

![](https://github.com/JosieBoyer/Credit_risk_analysis/blob/main/SMOTEENN.PNG)had a balanced score of 54.4%

![](https://github.com/JosieBoyer/Credit_risk_analysis/blob/main/easyA.PNG) Easy Ensemble AdaBoost had a balanced score of 93.1%. Very high precision and recall.

![](https://github.com/JosieBoyer/Credit_risk_analysis/blob/main/BRFC.PNG) BRFC had a balanced accuracy score of 78.8%. Had high average precision and recall.

## Summary
The oversampling, undersampling, and combination methods had comparatively low balanced accuracy scores. Easy Ensemble AdaBoost had a balanced score of 93.1%, which far and away outperformed the other models. I would reccommend using this as a tool to help predict credit-risk.
