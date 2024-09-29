# Spam-Email-Classification-using-Logistic-Regression-and-Text-Feature-Extraction-Techniques

This Spam Mail Prediction project focuses on developing a machine learning model to classify emails as either "spam" or "ham" (not spam) using logistic regression. The process involves several key stages:
1. Data Collection and Preprocessing:
The dataset used contains two columns: "Message" (the email content) and "Category" (spam or ham label).
Initial data cleaning includes handling missing values and encoding categorical labels (spam = 0, ham = 1).
2. Feature Extraction:
The text data is transformed into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization, which helps quantify the importance of words in each message relative to the dataset.
3. Model Training:
A Logistic Regression model is trained using these TF-IDF vectors to establish a relationship between the characteristics of the text and its classification.
The training set is split into training and testing subsets for model evaluation.
4. Evaluation:
The trained model is tested on unseen data, achieving an accuracy of around 96.6%. This high performance suggests that the model generalizes well for email classification tasks.
This project demonstrates how logistic regression and text feature extraction techniques can be effectively applied to solve text classification problems in a supervised learning context.
