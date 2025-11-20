# Phishing-Website-Detection-Using-Random-Forest-Algorithm
🛡️ Phishing Website Detection

A Machine Learning project that detects phishing URLs using feature extraction and a Random Forest classifier.

📌 Overview

This project builds a phishing-website detection system using URL-based features.
It extracts lexical features from raw URLs (length, presence of special symbols, digit count, suspicious patterns, etc.) and trains a Random Forest Classifier to classify websites as Phishing or Legitimate.

The model achieves reliable performance and can be used for browser extension security, email filtering, and cybersecurity applications.
 
🧠Features Extracted From URLs
 ---
The notebook extracts various handcrafted features, including:
- URL length  
- Number of digits  
- Number of special characters  
- Presence of HTTPS  
- Presence of IP address  
- Number of subdomains  
- URL path/query length  
- Suspicious keyword checks (e.g., login, verify, secure)


These features are transformed into a DataFrame and used for training.

🛠️Tech Stack
---
- Python 3
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn
- Joblib (for model saving)


🛠️ Model Pipeline
---
1. Import the dataset link(https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls)  
2. Define URL feature extraction function  
3. Extract features from each URL  
4. Split the dataset into training and testing sets  
5. Train the Random Forest classifier  
6. Evaluate the model (accuracy, precision, recall, confusion matrix)  
7. Visualize results  
8. Save the trained model using joblib  

