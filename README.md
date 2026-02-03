Sampling Assignment – Credit Card Fraud Detection
Objective

The objective of this assignment is to understand the importance of sampling techniques and analyze how different resampling strategies (for imbalanced data) affect the performance of various machine learning models on a credit card fraud detection dataset.

Dataset Description

Dataset Name: Creditcard_data.csv

Target Variable: Class

0 → Non-Fraud

1 → Fraud

The dataset is highly imbalanced, making resampling an essential preprocessing step.

Machine Learning Models Used
Model ID	Model Name
M1	Logistic Regression
M2	Decision Tree
M3	Random Forest
M4	K-Nearest Neighbors
M5	Support Vector Machine (SVM)
Sampling Techniques Used
Sampling ID	Sampling Technique
Sampling1	SMOTE
Sampling2	ADASYN
Sampling3	Random Under Sampling
Sampling4	Random Over Sampling
Sampling5	SMOTEENN
Methodology

Load the dataset

Split into training and testing sets

Apply feature scaling

Apply different sampling techniques on training data

Train five machine learning models on each sampled dataset

Evaluate model performance using accuracy

Compare results across models and sampling techniques

Accuracy Results

(Generated automatically by code as a table & pivot matrix)

Individual accuracy table

Pivot table (Model × Sampling)

Best sampling-model pair

Graphical Analysis
Accuracy Comparison Across Sampling Techniques

A bar chart comparing accuracy of all five models under different sampling methods.

Best Sampling Technique per Model

The best performing sampling technique is automatically selected for each model.

Observations

Oversampling improves minority class learning

SMOTE and ADASYN generally perform better than under-sampling

Tree-based models and Random Forest show strong performance

SVM is sensitive to sampling strategy

No single sampler is best for all models

Conclusion

Sampling techniques significantly influence machine learning performance on imbalanced datasets.
The experiment shows that choosing the correct sampling method is as important as selecting the model itself.

Learning Outcomes

Understood class imbalance problems

Learned multiple sampling strategies

Observed their impact on ML models

Gained experience in model comparison

Author

Yuvraj Sharma
