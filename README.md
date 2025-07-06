1st Model House_Pricing

✅ Best Model Configuration:
- Algorithm: Ridge Regression (alpha=0.1)
- Features: 15 polynomial features
- Cross-val Score: 0.812

📊 Performance Metrics:
Training Set:
- RMSE: 0.6523 
- R²: 0.8012

Test Set:
- RMSE: 0.6895
- R²: 0.7834


Visualization :->

Residual Plot: Diagnosing model errors across price ranges
Feature Importance: Identifying key price determinants
Actual vs Predicted: Visualizing model accuracy




2nd Model Spam Email Classifier

A robust spam email classification system using advanced NLP techniques and machine learning, designed to handle real-world data challenges with multiple fallback mechanisms.


🛠️ Robust Text Processing
Multi-stage cleaning: URL removal, email pattern removal, HTML stripping
Resilient tokenization: Falls back to simple tokenizer if NLTK fails
Lemmatization: Uses WordNet for word normalization
Error handling: Gracefully processes malformed text


📊 Data Pipeline
Automatic dataset acquisition: Downloads from GitHub with local fallback
Synthetic data generation: Creates training data if downloads fail
Feature engineering: Message length, word count, and TF-IDF features


🤖 Machine Learning
Multiple classifiers: Naive Bayes, Random Forest, and SVM
Model evaluation: ROC AUC, confusion matrices, classification reports
Error-resistant training: Isolated model training with fallbacks


✅ NLTK resources successfully downloaded
✅ Dataset loaded from GitHub

Dataset shape: (5572, 2)

Preprocessing text...
Remaining samples: 5550

Training Naive Bayes...
✅ Naive Bayes trained successfully
              precision    recall  f1-score   support

           0       0.98      1.00      0.99       965
           1       0.98      0.89      0.93       150

    accuracy                           0.98      1115
   macro avg       0.98      0.94      0.96      1115
weighted avg       0.98      0.98      0.98      1115

