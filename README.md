# Automated Phishing Detection using Machine Learning

This repository contains the code and configurations for an automated phishing detection system using machine learning. The system utilizes the XGBoost classifier to detect malicious URLs based on features extracted from phishing and legitimate URL datasets.

## Key Features

- 🖥️ **Machine Learning Model:** XGBoost classifier for URL classification.
- 🛡️ **Dataset Collection:** Datasets collected from Kaggle.
- 🔍 **Feature Extraction:** 17 features extracted from URLs for accurate detection.
- 📊 **Accuracy:** Achieved 86.4% accuracy in phishing detection.
- 🌐 **Real-Time Detection:** Deployed model for real-time phishing detection.
- 🔄 **Security Enhancement:** Improved online security by identifying malicious URLs.

## Project Overview

This project aims to detect phishing attacks by analyzing URLs using machine learning techniques. The key steps include dataset collection, feature extraction, model training using XGBoost, and deployment for real-time detection.

## Dataset Details

- **PhishTank Dataset:** Contains a collection of malicious (phishing) URLs.
- **Kaggle Dataset:** A comprehensive dataset of both phishing and legitimate URLs.
  
Both datasets were used to train and test the model.

## Model Training

1. **Data Preprocessing:** The raw data from Kaggle was cleaned and preprocessed.
2. **Feature Engineering:** 17 URL features were extracted for model training.
3. **XGBoost Classifier:** The XGBoost classifier was trained on the processed data to detect phishing URLs.
4. **Accuracy:** The model achieved an accuracy of 86.4% in detecting malicious URLs.

## Real-Time Detection

The trained model was designed to be deployed for real-time phishing detection, allowing the system to evaluate incoming URLs and flag potential phishing attempts

## Technologies Used

- 🔧 **Programming Language:** Python
- 🤖 **Machine Learning Algorithm:** XGBoost
- 📚 **Libraries/Tools:** scikit-learn, Pandas, NumPy
- 🧪 **Dataset Sources:** PhishTank, Kaggle
- 🌐 **Deployment:** Django (for web app)

