Project Description: Spam Mail Prediction Using Machine Learning

This project focuses on building a machine learning model to automatically classify emails as spam or legitimate (ham). Email spam filtering is an important application of Natural Language Processing (NLP) that helps improve email security and user experience by detecting unwanted or malicious messages.

The project uses a labeled dataset of email messages, where each email is categorized as spam or ham. The dataset is first processed using Python and Pandas to clean the data and handle missing values. The categorical labels are then converted into numerical form using label encoding, where spam is represented as 0 and ham as 1.

The text data from the emails is converted into numerical features using the TF-IDF (Term Frequency–Inverse Document Frequency) Vectorizer, which transforms textual messages into feature vectors that machine learning algorithms can understand.

The dataset is split into training and testing sets using Scikit-learn's train_test_split function. A Logistic Regression model is then trained on the training dataset to learn patterns that distinguish spam emails from legitimate ones.

After training, the model's performance is evaluated using accuracy scores on both training and test datasets to measure how well the model generalizes to unseen data. Finally, a predictive system is built that allows users to input a new email message, and the model predicts whether it is Spam or Ham.

The project demonstrates the practical use of machine learning and natural language processing techniques for text classification, which is widely used in email filtering systems and cybersecurity applications.
