# Fraud Detection Project

Team Members:

Ahmed Mahmoud

Omar Ahmed

Ahmed Ramy

Seif Tarek


Healthcare fraud costs the U.S. system more than $68 billion annually, and existing rule-based detection systems often miss sophisticated fraudulent behaviors.
This project develops a data-driven, explainable fraud detection model using real Medicare data from the Healthcare Provider Fraud Detection dataset.

# Our objective was to design an end-to-end pipeline that:

Detects fraudulent Medicare providers

Handles severe class imbalance (~10% fraud)

Ensures interpretability for regulators

Provides reliable, business-impactful predictions

The project follows an industry-style ML workflow including data understanding, feature engineering, model development, comparison, evaluation, and error analysis.


# Algorithms Compared

Implemented and evaluated:

Logistic Regression

Random Forest

Gradient Boosting

# Reasons for Choosing Logistic Regression:

Best performance on key metrics for imbalanced datasets

Strong generalization on unseen data

High interpretability (important for CMS fraud investigations)

Low risk of overfitting compared to tree-based models

Thus, Logistic Regression was selected as the final model for test-set evaluation.

# Dataset used: 
Healthcare Provider Fraud Detection (Available in GitHub repository alongside datasets after cleaning and datasets after aggregation)
Source: Kaggle
(If Git LFS doesn't work properly, please use this link (https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis) and run the code to get the cleaned datasets and the aggregated dataset)
