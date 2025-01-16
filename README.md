# Sentiment-Classifier-LELA-60331

5 Versions of a sentiment classifier that is trained on 36,547 labeled Amazon reviews to be able to identify either a positive or negative sentiment. The models are evaluated on precision, recall and accuracy. 

Version 1
Logisitic regression model with a frequency based vocabulary of 5k and tokeniser.

Version 2 
Logisitic regression model with a frequency based vocabulary of 10k and tokeniser including removing stopwords.

Version 3
Logisitic regression model with a class-frequency based vocabulary of 16k and tokeniser including removing stopwords.

Version 4
Multi-layer neural network with a frequency based vocabulary of 5k and tokeniser including removing stopwords and punctuation. 3 nodes in the hidden layer. 

Version 5
Multi-layer neural network with a frequency based vocabulary of 5k and tokeniser including removing stopwords and punctuation. 6 nodes in the hidden layer and a dev set showing loss and weights change over time. 

The best performing model is Version 5 with 70% accuracy, 66% recall and 94% precision.
