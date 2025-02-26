# Stock-Market-Predictions
This project uses NLP, which is focused on understanding and communicaiton with human languages. The two primary pre-processing methods involved tokenization and vectorization. We assessed sentiment from news articles, social media posts, and financial reports. You will find the datasets used in the code as it is from Colab. To continue this project, I am working on developing trading algorithms that respond to textual data, such as news releases or social media updates. 

Data-wise, 2037 train entries and 227 test entries. There were two fields, the sentence and the label. The NN predicts the label from the sentence which must be tokenized and vectorized. 

Pre-Processing:
Add the token [CLS] to the beginning of the sentence and [SEP] to the end 
Split the sentence into a list of words and punctuation
Map each word to its index in BERT
Add padding elements to the end of the sentence so that all sentences are the same length
Generate the Attention Mask – holds a 0 if the corresponding index in the tokenized sentence is a placeholder and a 1 otherwise

Models used: BERT, RNN, and LSTM

Accuracy of model: 97.8% under current parameters
