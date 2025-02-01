# SMS-Spam-Detection-

## Project Overview
This project aims to classify SMS messages as either spam or legitimate (ham) using machine learning techniques. By leveraging natural language processing (NLP), we build models that can accurately detect spam messages, helping users filter unwanted content.

## Business Understanding
### Stakeholders:
- Mobile network operators
- Messaging service providers
- End-users looking to reduce spam messages

### Business Problem:
Unsolicited SMS spam messages cause inconvenience and may contain phishing attempts. Automated spam detection can improve user experience and security by reducing exposure to such messages.

## Data Understanding
### Dataset Used:
- **Dataset Name:** SMS Spam Dataset
- **Timeframe:** [Specify timeframe if known]
- **Key Features:**
  - Message Text
  - Spam or Ham Label

### Data Limitations:
- Possible language and regional biases in spam detection.
- Dataset may not include new spam trends.
- Short text length may limit model accuracy.

## Modeling and Evaluation
### Models Used:
- Naive Bayes Classifier
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

### Evaluation Metrics:
- Accuracy
- Precision & Recall
- F1 Score
- ROC-AUC Score

## Conclusion
### Key Findings:
- Certain keywords and message structures strongly indicate spam.
- Preprocessing techniques (e.g., stemming, stopword removal) improve classification accuracy.
- Naive Bayes performs well for text classification tasks due to its probabilistic nature.

### Recommendations:
- Implement the model in messaging apps for automatic spam filtering.
- Update the dataset regularly to detect new spam trends.
- Explore deep learning techniques like LSTMs for better text classification.

### Future Steps:
- Expand dataset with more diverse spam messages.
- Deploy model as an API for real-time spam detection.
- Improve feature engineering techniques to enhance model performance.


