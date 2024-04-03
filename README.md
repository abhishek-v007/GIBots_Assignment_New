GIBots Assignment Description
To create a ML model that predicts the probability that a piece of text belongs to a particular class, we can use the following techniques:

Bag of Words: This is a simple and effective technique for text classification. We can create a bag of words by counting the frequency of each word in the text. We can then use this bag of words as input to our ML model.
TF-IDF Vectorization: This is another popular technique for text classification. It converts the text into a numerical representation that takes into account the frequency of each word in the text as well as the importance of the word in the entire dataset.
Word Embedding: This is a more advanced technique that represents each word as a dense vector in a high-dimensional space. This allows the model to capture the semantic meaning of each word.

To use the Hash field value, we can use it as an additional feature in our ML model. The Hash field value is a cryptographic hash of the raw text, which can be used to identify unique text samples. We can use this hash value to ensure that our model is not biased towards any particular text sample.

Here is an example of how we can create a ML model using Bag of Words and the Hash field value:

Load the train.csv and trainLabels.csv files into pandas dataframes.
Extract the text from the "Content" column in the train.csv file.
Create a bag of words by counting the frequency of each word in the text.
Use the bag of words as input to a ML model, such as a logistic regression model.
Use the Hash field value as an additional feature in the ML model.
Train the ML model on the training data.
Load the test.csv file into a pandas dataframe.
Extract the text from the "Content" column in the test.csv file.
Create a bag of words for the test data using the same method as before.
Use the trained ML model to predict the probability that each test sample belongs to each class.
Format the predictions into the required submission format.

