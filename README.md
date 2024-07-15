
# Spam Email Detection

This project aims to classify emails as spam or ham (not spam) using machine learning techniques. The dataset used is the SMS Spam Collection Dataset from Kaggle.

## Project Overview

- **Dataset**: [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
- **Goal**: Detect spam emails using a Naive Bayes classifier.
- **Techniques Used**: Text preprocessing, TF-IDF vectorization, Naive Bayes classification.

## Steps Involved

1. **Data Preprocessing**:
   - Cleaning and preparing the text data.
   - Handling missing values.

2. **Feature Extraction**:
   - Converting text data into numerical vectors using TF-IDF.

3. **Model Training**:
   - Training a Naive Bayes classifier on the processed data.

4. **Evaluation**:
   - Evaluating the model’s performance using accuracy score and classification report.

## Usage

### 1. Install Dependencies

!pip install pandas scikit-learn

### 2. Set Up Kaggle API
Upload kaggle.json with your Kaggle API credentials.

### 3. Download and Unzip Dataset
!kaggle datasets download -d uciml/sms-spam-collection-dataset
!unzip sms-spam-collection-dataset.zip

### 4. Run the Code
Follow the provided Jupyter notebook or Python script to preprocess data, train the model, and evaluate the results.

Results
The project demonstrates the process of detecting spam emails with a high level of accuracy using a simple yet effective Naive Bayes classifier.

Future Work
Implementing more advanced models like SVM or deep learning techniques.
Adding more feature engineering techniques to improve model accuracy.

