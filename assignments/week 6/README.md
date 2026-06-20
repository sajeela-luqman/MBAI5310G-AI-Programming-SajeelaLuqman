## Week 06– Model Evaluation, Explainability, and Fairness Reflection
# Task Overview
Train the data, clean the data, and apply model evaluation, explanation, and fairness by using SHAP and LIME.   

# Files in This Folder
bank_product_subscription_dataset.csv main notebook for the task

# Dataset or Input Source
The datasets that I used for this purpose were "bank_product_subscription_dataset.csv".
For the bank product subscription, our target was to check if the clients would buy the product. 
# Methods Used
After building, training, and cleaning the dataset, I continued the given data to apply SHAP and LIME and checked the difference by gender and age group. 
Target Variable:subscribed (0 = Did Not Subscribe, 1 = Subscribed)  
Model Used: Decision Tree Classifier 

Business Interpretation: The model is an early prototype. Recall is the critical metric for this marketing use case. Overfitting is present, and class imbalance should be addressed before production use.  

Limitation: The dataset is imbalanced (32% subscribed), which reduces the model's ability to correctly identify true subscribers.
# Key Results
After completing all results,
Main Results: Accuracy: 65.4% | Recall: 40.0% | F1-Score: 42.6%   

# Limitation
The dataset is simple, but this kind of data is not easy; it could be more complex than that, so it may not generalize well to a real-world dataset.   


