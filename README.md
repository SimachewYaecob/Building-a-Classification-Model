

**Classification Model**

**Project Title:** Building a Classification Model 

**Description:** Use the breast cancer dataset to build and evaluate a classification model (e.g., logistic regression, decision tree). Compare model performance using metrics like accuracy and F1 score. 

**Dataset Reference:** Breast Cancer Wisconsin Dataset 

**Steps followed**

1.	Study the dataset
   
2.	Cleaning the data
   
3.	Split Features and Target Variable
   
4.	Feature Scaling
   
5.	Train-Test Split
    
6.	Training & Evaluation
    
7.	Creating a summary table for comparison different classification model


**Insights and Conclusion** 


1.	Logistic Regression, SVM, and Neural Network all achieved the highest accuracy and F1 score (0.9737 and 0.9647), indicating excellent performance in identifying both benign and malignant cases. High F1 score suggests a strong balance between precision and recall, which is crucial in medical diagnoses where false negatives can be dangerous. 

2.	Logistic Regression, SVM, and Neural Network are the most effective and should be considered first for deployment. 

3.	Random Forest and Naive Bayes performed slightly below the top models but still showed strong accuracy and F1 scores (> 0.95), making them reliable and less computationally intensive alternatives. 

4.	Gradient Boosting, Decision Tree, and K-Nearest Neighbors had lower accuracy and F1 scores (around 0.94–0.95). These may be more prone to overfitting or underperformance compared to ensemble or linear models in this dataset. So, Decision Tree and KNN may not generalize as well but can still be used for baseline comparisons. 

5.	Why did ensemble models like Gradient Boosting perform worse compared to Logistic Regression, SVM, and Neural Networks? This could be because ensemble models combine multiple learners, and their aggregated decision might not always capture complex patterns as effectively in certain datasets. 

