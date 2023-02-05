# Supervised ML & Sentiment Analysis

In supervised machine learning, you usually have an input
�
X, which goes into your prediction function to get your
�
^
Y
^
. You can then compare your prediction with the true value
�
Y. This gives you your cost which you use to update the parameters
�
θ.

# Vocabulary & Feature Extraction

# Feature Extraction with Frequencies

# Preprocessing

1. Eliminate handles and URLs

1. Tokenize the string into words.

1. Remove stop words like "and, is, a, on, etc."

1. Stemming- or convert every word to its stem. Like dancer, dancing, danced, becomes 'danc'. You can use porter stemmer to take care of this.

1. Convert all your words to lower case.

# Logistic Regression

Logistic regression makes use of the sigmoid function which outputs a probability between 0 and 1.

# Logistic Regression: Training

You initialize your parameter
�
θ, that you can use in your sigmoid, you then compute the gradient that you will use to update
�
θ, and then calculate the cost. You keep doing so until good enough.

# Logistic Regression: Testing
