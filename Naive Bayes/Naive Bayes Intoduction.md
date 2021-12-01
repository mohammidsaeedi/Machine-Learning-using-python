Naive Bayes using Bayes theorem we can find the probability of A, given that B occurred. A is the hypothesis and B is the evidence.

Gaussian: It is used in classification and it assumes that features follow a normal distribution.

Multinomial: It is used for discrete counts. For example, let’s say,  we have a text classification problem. Here we can consider Bernoulli trials which is one step further and instead of “word occurring in the document”, we have “count how often word occurs in the document”, you can think of it as “number of times outcome number x_i is observed over the n trials”.

Bernoulli: The binomial model is useful if your feature vectors are binary (i.e. zeros and ones). One application would be text classification with ‘bag of words’ model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.

We are taking a dataset of chemical analysis of wines, 
our aim is to create a model to find different cultivars of the three cultivars, wines grown in the same region in Italy but derived from three different cultivars.
[For more](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
