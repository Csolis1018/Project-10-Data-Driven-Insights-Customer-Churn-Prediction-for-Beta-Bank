# Data-Driven Insights: Customer Churn Prediction for Beta Bank

This project aims to predict customer churn at Beta Bank using historical customer behavior and contract termination data. Since retaining existing customers is more cost-effective than acquiring new ones, the goal is to build a reliable machine learning model that identifies customers likely to leave the bank.

# Objective

To test the following hypothesis:

Customer behavioral and demographic data can be used to predict churn with a strong classification performance, achieving an F1 score of at least 0.59, while also evaluating the model using the AUC-ROC metric.

# 🛠️ Technologies Used

Python: Pandas, NumPy, Scikit-learn

Jupyter Notebook: Interactive environment for model training and evaluation

CSV Dataset: Contains customer demographic and behavioral data

# Key Steps
# Data Description

Loaded and explored the dataset to understand feature distributions and data types.

Identified the target variable (Exited) and relevant numerical and categorical features.

Examined class balance to assess the degree of churn imbalance.

# Data Preprocessing

Cleaned and prepared the dataset for modeling.

Encoded categorical variables and scaled numerical features where necessary.

#Baseline Modeling

Trained initial classification models without addressing class imbalance.

Evaluated baseline performance using the F1 score.

Identified limitations caused by class imbalance.

# Handling Class Imbalance

Applied at least two techniques to address class imbalance, such as:

Class weight adjustment

Resampling techniques

Compared model performance after applying each approach.

# Model Selection and Tuning

Trained multiple models using training and validation sets.

Tuned hyperparameters to maximize the F1 score.

Selected the best-performing model based on validation results.

Model Evaluation

Evaluated the final model using the test dataset.

Measured both F1 score and AUC-ROC to assess classification quality.

Compared both metrics to gain a comprehensive understanding of model performance.

#vResults

The analysis demonstrates that:

Customer churn can be effectively predicted using behavioral and demographic features.

Addressing class imbalance significantly improves the model’s F1 score.

The final model achieved an F1 score exceeding 0.59 on the test set.

The AUC-ROC metric confirms that the model is capable of distinguishing between churned and retained customers.

These results show that Beta Bank can leverage this model to proactively identify at-risk customers and implement retention strategies more efficiently.
