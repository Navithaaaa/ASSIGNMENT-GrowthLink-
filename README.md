# ASSIGNMENT-GrowthLink-
Project Overview

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset includes information such as age, gender, class, and fare paid. The model is trained on historical data to classify passengers as survivors or non-survivors.

Preprocessing Steps

The dataset is first loaded using Pandas. Data cleaning involves handling missing values in columns such as Age, Cabin, and Embarked, where missing values are filled using appropriate strategies, such as the median for Age and the most common value for Embarked. Feature engineering techniques include extracting titles from passenger names, creating a new feature for family size, and converting categorical variables like Sex and Embarked into numerical formats. Finally, numerical features are standardized, and categorical features are one-hot encoded to prepare the dataset for machine learning models.

Model Selection

Model selection was based on accuracy and performance metrics using cross-validation.
Random Forest Classifier was evaluated and achieved a good predictabily.

Performance Analysis

The model were evaluated using multiple metrics to determine its effectiveness. Accuracy score was used as a general measure of performance, while the confusion matrix provided insights into classification errors. Precision, recall, and F1-score were analyzed to understand the model's ability to correctly classify survival outcomes, particularly in imbalanced scenarios. Additionally, the ROC-AUC curve was used to assess the classifier’s effectiveness in distinguishing between survivors and non-survivors. The best-performing model was selected based on the highest accuracy and balanced precision-recall scores.


