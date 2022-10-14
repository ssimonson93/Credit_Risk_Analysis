# Overview of Analysis
The purpose of this project was to use machine learning in order to predict loan risk.  Multiple machine learning models were built, trained, and used to test for high and low risk loans.  The credit card credit dataset was oversampled using RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm.  Then, a combination of the two was used via the SMOTEENN algorithm.  Finally, the BalancedRandomForestClassifier and EasyEnsembleClassifier techniques were used.  All of these techniques were compared to determine which machine learning model was best able to predict credit risk.

# Results
The results of the different machine learning models were as follows.
* After testing using the RandomOverSampler method, the prediction’s accuracy score was 0.62, the precision score was 0.99, and the recall score was 0.65.
* After testing using the SMOTE method, the prediction’s accuracy score was 0.65, the precision score was 0.99, and the recall score was 0.66.
* After testing using the ClusterCentroids method, the prediction’s accuracy score was 0.51, the precision score was 0.99, and the recall score was 0.44.
* After testing using the SMOTEENN method, the prediction’s accuracy score was 0.65, the precision score was 0.99, and the recall score was 0.58.
* After testing using the BalancedRandomForestClasifier method, the prediction’s accuracy score was 0.8, the precision score was 0.99, and the recall score was 0.91.
* After testing using the EasyEnsembleClassifier method, the prediction’s accuracy score was 0.93, the precision score was 0.99, and the recall score was 0.94.

# Summary
Each machine learning model achieved a precision score of 0.99, however, the accuracy and recall scores varied much more.  The lowest recall and accuracy scores were seen in the undersampled model using the ClusterCentroids method, while the highest recall and accuracy scores were seen using the EasyEnsembleClassifier method.  Due to this, the recommended model for this data would be the EasyEnsembleClassifier method.
