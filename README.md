#### SMS_spam_detection
 Afama_technologies'####

 **SMS Spam Detection Project**

Copyright © 2024 Sushain Devi

This project aims to build a machine learning model for detecting spam messages in SMS data. The dataset used for this project contains SMS messages labeled as either "ham" (non-spam) or "spam". The goal is to develop a model that can accurately classify incoming messages as spam or non-spam.

**Dataset**
- The dataset used in this project is sourced from a CSV file named `spam.csv`.
- It contains two columns: "label" indicating the class label ("ham" or "spam") and "sms" containing the text of the SMS messages.

**Data Preprocessing**
- The dataset underwent preprocessing steps, including removing unnecessary columns and renaming columns for clarity.
- Text preprocessing techniques such as converting text to lowercase, removing punctuation, and tokenizing were applied to prepare the text data for modeling.

**Feature Engineering**
- Bag-of-Words (BOW) approach was employed to represent text data numerically.
- CountVectorizer was used to convert text data into numerical feature vectors.

**Model Building**
- The Multinomial Naive Bayes classifier was chosen as the model for this task due to its effectiveness in text classification tasks.
- The training data was used to train the model, and class weights were adjusted to handle class imbalance.
- The trained model was then used to make predictions on the testing data.

**Evaluation**
- Various evaluation metrics such as accuracy, precision, recall, and F1-score were computed to assess the performance of the model.
- A confusion matrix was generated to visualize the performance of the model in classifying spam and non-spam messages.

**Results**
- The model achieved satisfactory performance in detecting spam messages, with high accuracy and precision.
- The confusion matrix provides insights into the model's ability to correctly classify spam and non-spam messages.

**Next Steps**
- Further tuning of hyperparameters and exploring different models to potentially improve performance.
- Deploying the trained model for real-time spam detection in SMS applications.

**Dependencies**
- Python 3.x
- Libraries: pandas, numpy, nltk, scikit-learn, matplotlib, seaborn

**Contributors**
- Sushain Devi
- GitHub: [Sushain Devi](https://github.com/SushainDevi)

**References**
- Dataset source: [Provide link to dataset source]
- Additional resources: [Any additional resources or papers referenced]
