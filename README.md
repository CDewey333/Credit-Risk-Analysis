Credit Risk Analysis
Using Supervised Machine Learning to Determine Credit Risk
Results
1.	Naive Random Oversampling
o	Precision: High Risk = 0.01; Low Risk = 1.00
o	Recall: High Risk = .72; Low Risk = 0.56
o	Balanced Accuracy Score = 0.64
o	Accuracy score is low
 
2.	SMOTE Oversampling
o	Precision: High Risk = 0.01; Low Risk = 1.00
o	Recall: High Risk = .62; Low Risk = 0.69
o	Balanced Accuracy Score = 0.65
o	Accuracy score is low
 
3.	Cluster Centroids Under sampling
o	Precision: High Risk = 0.01; Low Risk = 1.00
o	Recall: High Risk = .69; Low Risk = 0.40
o	Balanced Accuracy Score = 0.54
o	Accuracy score is low
 
4.	SMOTEENN (Combination of Over and Under sampling)
o	Precision: High Risk = 0.01; Low Risk = 1.00
o	Recall: High Risk = .73; Low Risk = 0.60
o	Balanced Accuracy Score = 0.66
o	Accuracy score is low
 
5.	Balanced Random Forest Classifier
o	Precision: High Risk = 0.03; Low Risk = 1.00
o	Recall: High Risk = .70; Low Risk = 0.87
o	Balanced Accuracy Score = 0.78
o	Accuracy score is low
 
6.	Easy Ensemble AdaBoost Classifier
o	Precision: High Risk = 0.09; Low Risk = 1.00
o	Recall: High Risk = .92; Low Risk = 0.94
o	Balanced Accuracy Score = 0.93
o	Accuracy score is low
 
Summary
•	At an accuracy of 0.54 Cluster Centroids Under sampling was the least successful algorithm in terms of accuracy.
•	On the other side of the spectrum the Easy Ensemble method yielded the highest level of accuracy at 0.93.
•	The Low-Risk precision didn't vary for any of the methods and sat a - 1.00.
•	The best high risk precision score was with the Easy Ensemble method at 0.09.
•	The recall scores for the Ensemble methods was better than the Oversampling/Under sampling/Combination algorithm.
Conclusion
When compared side by side for this population it would seem that the Easy Ensemble AdaBoost Classifier algorithm is the most effective strategy to determine credit risk. It had the highest level of accuracy and at 0.93. This is 15% higher than the next best strategy (Balanced Random Forest). The AdaBoost algorithm was able to predict high risk with a 0.92 level of accuracy and low risk with 0.94 level of accuracy. At scale this would save the company hundreds of thousands of dollars that the other models may not protect the company from. This level of accuracy would also greatly increase the level of customer satisfaction with far less rejections of qualified borrowers.

