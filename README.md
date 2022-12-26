# iPADD
Introduction
----------------
Diabetes Mellitus is a chronic metabolic disease that causes an increasing number of people to have an imbalance in blood glucose homeostasis, which can lead to severe complications. Hence, the accurate prediction of potential drugs for the treatment of diabetes will speed up the development of antidiabetic drugs and save researchers time and expense. The object of this work was to build a classifier for antidiabetic drugs to predict whether a drug has the potential to treat diabetes. In this study, four molecular fingerprints and their combinations were used to encode the drugs separately and features were screened using minimum-Redundancy-Maximum-Relevance(mRMR) and incremental feature selection (IFS) strategies. Based on the optimal feature subset, models were trained by eight machine-learning algorithms with 5-fold cross-validation. XGBoost model based on the combination of E+F+M molecular fingerprints had an accuracy (ACC) and the area under the receiver operating characteristic curve (auROC) value of 0.983 and 0.989 on the independent test set. 


Required Package
------------
Python3 (tested 3.9.12)  
numpy (tested 1.23.1)  
pandas (tested 1.4.3)  
jupyter (tested 1.0.0)  
scikit-learn (tested 1.1.1)  
rdkit(tested 2022.3.4)  


Usage
--------------------------
Enter the name of the compound as a txt file  
Train and load model by using:  
'XGBoost Model.ipynb'  
The possibility of predicting compounds for the treatment of diabetes by using:  
'predict.ipynb'  
