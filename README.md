# Sentiment-analysis
- use machine learning model Support vector machine and RNN model 
- in RNN deep model we're using the Keras imdb dataset, which provides preprocessed movie reviews from IMDb
- load the dataset and limit the number of features to consider using max_features. Next, we pad the sequences to have the same length using maxlen.
- The LSTM-based RNN model consists of an embedding layer this layer maps input information from a high-dimensional to a lower-dimensional space, allowing the network to learn more about the relationship between inputs and to process the data more efficiently, LSTM layer with dropout to prevent overfitting
- and a dense layer with a sigmoid activation function for binary classification
- We compile the model using binary cross-entropy as the loss function and the Adam optimizer.
