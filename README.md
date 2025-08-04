# Predicting-Personality-Traits-from-Selfie-Data-An-Exploratory-Analysis

This project explores the fascinating intersection of artificial intelligence and personality psychology by attempting to predict personality traits from selfie data. The primary goal was to build a machine learning model capable of predicting a person's extroversion score based on a variety of features, including other personality scores (confidence, trustworthiness), visual cues (smile intensity, eye contact), and demographic information (age, gender).

The project began with a comprehensive exploratory data analysis (EDA) to understand the distributions of the personality scores and their relationships with other variables. This involved creating visualizations such as histograms and box plots to uncover initial insights and patterns in the data.

Following the EDA, we preprocessed the data by one-hot encoding categorical features to prepare them for machine learning models. We then built and evaluated two different regression models: a Random Forest Regressor and a Linear Regression model.

Despite our efforts, both models performed poorly on the available dataset, which was very small (20 samples). The negative R-squared values indicated that the models were not able to capture the underlying patterns in the data. However, the feature importance analysis from the Random Forest model suggested that trustworthiness_score, confidence_level, and eye_contact_score were the most influential features in predicting extroversion.

This project serves as a valuable case study in the challenges of working with small datasets and highlights the importance of data quality and quantity in machine learning. Future work should focus on acquiring a larger and more diverse dataset to build more robust and accurate predictive models.
