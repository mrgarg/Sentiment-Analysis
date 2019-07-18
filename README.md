# Sentiment-Analysis
###  Analysis of movie reviews with the help of Neural Network.

Sentiment analysis is a vital topic in the field of NLP.It is the process of ‘computationally’ determining whether a piece of writing is positive,negative.It’s also known as opinion mining,deriving the opinion or attitude of a speaker.

For this analysis i used a dataset of 50,000 movie reviews taken from IMDb.The data is split evenly with 25k reviews intended for training and 25k for testing your classifier. Moreover, each set has 12.5k positive and 12.5k negative reviews.
IMDb lets users rate movies on a scale from 1 to 10. To label these reviews the curator of the data labeled anything with ≤ 4 stars as negative and anything with ≥ 7 stars as positive. Reviews with 5 or 6 stars were left out.

The analysis is done with the help of **Neural Network**.

## In the Network Building i use a
 • fully connected /dense layer with relu activation
 • 2 hidden layer with 16 neurons
 • 1 output layer with 1 neuron( sigmoid activation)
 
**By using above model i got 87 % accuracy on test set and 94 % accuracy on training set.**
