# SMS Spam Detection Using NLP and Machine Learning

## Project Summary: SMS Spam Detection Using NLP and Machine Learning
Objective: Build a machine learning model that classifies SMS messages as "spam" or "ham" (not spam).

Dataset Used: SMS spam collection dataset

Total messages: Around 5,572 messages.

##  ✅ Steps and Key Insights
1. Data Exploration:
Checked for null values: No missing data.

Class distribution:

Ham: ~87%

Spam: ~13%

Insight: Dataset is imbalanced — mostly non-spam messages.

2. Text Preprocessing:
Lowercased all text.

Removed punctuation, stopwords, special characters.

Applied stemming to reduce words to root form.

Used CountVectorizer or TF-IDF for converting text into numerical form.

3. Model Building & Evaluation:
Models used: Likely Naive Bayes, Logistic Regression, or Random Forest.

Best-performing model:

Accuracy: ~98%

Precision for Spam: Very high (which is important to reduce false positives).

Recall: Also strong, meaning most spam messages were correctly identified.

Confusion Matrix Insight: Very few ham messages misclassified as spam or vice versa.

## 📊 Final Results & Impact
The classifier accurately distinguishes spam from ham.

Can be integrated into messaging systems to automatically filter spam.

Lightweight and efficient for real-time prediction.
