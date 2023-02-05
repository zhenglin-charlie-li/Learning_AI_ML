# Probability and Bayes’ Rule

# Bayes' Rule

![image](https://user-images.githubusercontent.com/63448884/216799609-56482051-8067-45b2-9538-b942226a341a.png)

# Naive Bayes

# Laplacian Smoothing

![image](https://user-images.githubusercontent.com/63448884/216799625-9b0c2bec-03e1-4015-872d-aaa664873bc0.png)

Note that we added a 1 in the numerator, and since there are V words to normalize, we add V in the denominator. 

# Log Likelihood

![image](https://user-images.githubusercontent.com/63448884/216799667-17e85c8d-81aa-4980-8e24-bd2e6efb72b4.png)

# Training naïve Bayes

1) Get or annotate a dataset with positive and negative tweets
2) Preprocess the tweets: process_tweet(tweet) ➞ [w1, w2, w3, ...]:
  - Lowercase

  - Remove punctuation, urls, names

  - Remove stop words

  - Stemming

  - Tokenize sentences

3) Compute freq(w, class)
4) 4) Get 
�
(
�
∣
�
�
�
)
,
�
(
�
∣
�
�
�
)
 
P(w∣pos),P(w∣neg) 
5) Get 
�
(
�
)
λ(w)
6) Compute 
�
�
�
�
�
�
�
�
=
log
⁡
(
�
(
�
�
�
)
/
�
(
�
�
�
)
)
logprior=log(P(pos)/P(neg))

# Applications of Naive Bayes
There are many applications of naive Bayes including: 

Author identification

Spam filtering 

Information retrieval 

Word disambiguation 

This method is usually used as a simple baseline. It is also really fast.

# Naïve Bayes Assumptions
assign equal weight to the words
in the real world, the data could be much noisier.  balanced to have to the same amount of positive and negative tweets

# Error Analysis
