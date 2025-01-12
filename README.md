# Spam_or_ham
SMS Spam Detection: Machine Learning Text Classification Project
Developed an advanced machine learning solution to automatically classify SMS messages as spam or legitimate (ham) using a comprehensive dataset of 5,574 labeled text messages. Implemented a sophisticated text classification model to enhance communication filtering and protect users from unwanted messages.
Data Collection: Utilized the SMS Spam Collection dataset with comprehensive labeling
Data Preprocessing:

Cleaned and transformed raw text messages
Prepared data for machine learning model training


Model Development:

Implemented classification algorithms
Trained model on labeled dataset
Validated model performance and accuracy


Classification Capabilities:

Automated detection of spam messages
Real-time text message evaluation

### Goal - To build a predictive model which will determine whether a text message is spam or ham. 

#### Multinomial Naive Bayes

Multinomial Naive Bayes algorithm is a probabilistic learning method that is mostly used in Natural Language Processing (NLP). The algorithm is based on the Bayes theorem and predicts the tag of a text such as a piece of email or newspaper article. It calculates the probability of each tag for a given sample and then gives the tag with the highest probability as output.

Bayes theorem, formulated by Thomas Bayes, calculates the probability of an event occurring based on the prior knowledge of conditions related to an event. It is based on the following formula:

P(A|B) = P(A) * P(B|A)/P(B)


Where we are calculating the probability of class A when predictor B is already provided.

P(B) = prior probability of B

P(A) = prior probability of class A

P(B|A) = occurrence of predictor B given class A probability

This formula helps in calculating the probability of the tags in the text.
