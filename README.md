# Credit-Card-Fraud-Detection
We used credit card customer data to predict fraudulent credit card users by using different machine learning algorithms.

Credit Card Approval Prediction Project
Overview
This project focuses on training a predictive model to determine whether a credit card application should be approved or denied based on historical data collected by lenders. The primary objective is to leverage machine learning techniques to accurately classify applicants as safe or risky, thus aiding lenders in their decision-making process.

Goal
The goal of this project was to utilize a dataset obtained from Kaggle, containing application record data and credit history data. By developing a machine learning model, the project aimed to predict whether an applicant should be approved for a credit card based on various features and historical credit records.

Dataset
The dataset was comprised of application and credit records, linked by a customer ID. The data posed certain challenges, including the one-to-many relationship between customers and their records. The dataset contained categorical and continuous features, along with payment status indicators for credit records.

Methodology
Data Preprocessing: The team converted categorical values to numerical ones, handled missing values, and engineered new features such as average payment status to label applicants as risky or not.

Feature Engineering: The credit records were grouped, and average payment status was calculated for each customer. A function was developed to label customers as risky if their average payment status exceeded a certain threshold.

Data Joining: The credit records were merged with application records using a customer ID inner join, ensuring only relevant data for modeling was retained.

Data Visualization: Data visualization techniques like scatter plots, histograms, and heatmaps were used to gain insights into the dataset and guide data cleaning.

Model Selection: Multiple classifiers, including logistic regression, random forest, decision tree, Gaussian, and K Neighbors, were trained and evaluated for accuracy and area under the ROC curve (AUC).

Results
The accuracy rates and AUC values for each classifier were as follows:

Logistic Regression: Accuracy - 0.6885, AUC - 0.5082
Random Forest: Accuracy - 0.7125, AUC - 0.7212
Decision Tree: Accuracy - 0.6962, AUC - 0.6430
Gaussian: Accuracy - 0.6885, AUC - 0.5043
K Neighbors: Accuracy - 0.7021, AUC - 0.6780
Conclusion
In this project, we successfully developed a machine learning model to predict credit card approval based on historical data. The Random Forest classifier demonstrated the highest accuracy among the models evaluated. The insights gained from data visualization and feature engineering played a crucial role in enhancing the model's performance. The project provides a solid foundation for further exploration and improvement in credit card approval prediction using more advanced techniques.


