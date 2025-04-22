
SMS Spam Classifier

This project contains a machine learning model that classifies SMS messages as spam or ham (non-spam). It uses natural language processing (NLP) techniques to analyze the text data and predict whether the message is spam or not w
ipnb file Preprocesses the text data ie data visualization then lowercase,tokenization, removing special character, removing stop words and punctucation, stemming
Vectorize the text data using TFID and count vectorizer for model builing 
Train naive based machine learning model (GaussianNB,MultinomialNB,BernoulliNB )
Evaluates the model's performance and choose best model (MNB) to create pickle file , which is later used in app.py file for prediction.
The model is hosted using Streamlit, where a pre-trained machine learning model, saved as a Pickle file, is loaded to classify SMS messages as spam or not through simple interactive web app.
 message-spam-classifier
classify the message as spam or not based on the trends and pattern seen in message with accuracy matrices of 98.3% and precision score of 99.1% 
