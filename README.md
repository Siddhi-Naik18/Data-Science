# Fake News Detection
## 📋 Project Overiew
This project aims to detect fake news by analyzing news articles using machine learning techniques. The process involves data preprocessing, feature extraction, and the implementation of multiple classification models to predict whether a news article is real or fake.
## 📊 Key Features
- Data Collection and Combination: Two datasets, one containing fake news and the other true news, are uploaded and merged into a single dataset for analysis.
- Data Preprocessing: The combined dataset undergoes preprocessing steps including shuffling, resetting indices, dropping unnecessary columns, and cleaning text data using a custom function `wordopt`.
- Data Splitting and Model Training: The cleaned dataset is split into 70% training data and 30% testing data. Machine learning models such as Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and Gradient Boosting Classifier are trained on the training data.
- Feature Extraction: Text data is transformed into numerical features through vectorization techniques to facilitate model training and prediction.
## 📂 Repository Structure
This repository contains the following files:
- `notebooks/`: Directory contains Jupyter notebooks for all 4 tasks.
- `README.me`: File provide with an overview of the project.
## 📝 Conclusion
The project concludes with insights into the effectiveness of different machine learning models in detecting fake news. Recommendations and strategies may be provided based on the model results to address the spread of misinformation and improve news credibility.
