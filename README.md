# Crash-Analysis-And-Safety-Testing
The rapid development and deployment of autonomous vehicles (AVs) presents significant safety challenges, particularly regarding the reliability and robustness of their machine learning (ML) models. This project aimed to address the gap in ensuring the safety of AVs by focusing on systematic crash scenario analysis and robust safety testing of their ML models.
# The key objectives were:
Exploratory Data Analysis (EDA)
The project conducted extensive EDA on the dataset, including visualizing the distributions of driver age and gender, as well as analyzing the trend of incidents over time and performing Principal Component Analysis (PCA).
# Data Preprocessing and Modeling
The dataset was split into training and testing sets, and the 'Totalinjuries' feature was binned into four categories. Categorical features were encoded using OneHotEncoder.
Several machine learning models were trained and evaluated, including:
Random Forest Classifier, which achieved an accuracy of 0.90 on the test set.
Gradient Boosting Classifier, which was also evaluated.
To address class imbalance, SMOTE oversampling was applied to the training data. The trained Random Forest Classifier model was also saved and loaded for further evaluation.
The project demonstrates the use of various techniques to analyze and predict the severity of crash injuries based on vehicle and crash parameters. The results highlight the need for continued research and development to ensure the safety of autonomous vehicles as they become more widely deployed.
