# The-Sentiment-Analysis-using-Tensorflow
 (by a tutorial from https://pythonprogramming.net)

My goal is to use a neural network to correctly identify sentiment of given text.
I have a file with about 5000 positive sentiment statements and 5000 negative.
First we need be converted the texts to a vector of features. Out texts have different length, but we need all feature sets to be exactly the same length.
I am am using "bag-of-words model."
The label can be "positive" or "negative". I will use one-hot encoding and have the label vector be [POS,NEG], where positive data is [1,0] and negative data would be [0,1].
For preprocessing I am going to use tokenizer and lemmatizer form nltk.

*************** output ************************

Epoch 1 completed out of 10 loss: 1297936.97656

Epoch 2 completed out of 10 loss: 513660.998047

Epoch 3 completed out of 10 loss: 302777.321655

Epoch 4 completed out of 10 loss: 389191.927185

Epoch 5 completed out of 10 loss: 242533.387436

Epoch 6 completed out of 10 loss: 75430.8634911

Epoch 7 completed out of 10 loss: 26345.9708228

Epoch 8 completed out of 10 loss: 21521.4770298

Epoch 9 completed out of 10 loss: 21017.0309887

Epoch 10 completed out of 10 loss: 19652.573164

Accuracy: 0.60788

I tried different number of nodes and layers, but the result was about the same. I think, the accuracy is so low since I used a very small dataset and it is critical for neural network to have a lot of data.
