# Sentiment-Analysis-using-Naive-Bayes
Twitter Sentiment Analysis (Two classes : Positive tweet / Negative tweet)

# Sentiment-Analysis-using-Naive-Bayes
Twitter Sentiment Analysis (Two classes : Positive tweet / Negative tweet)

Based on Conditional Probabilities,
Bayes rule is based on mathematical formation of conditional probabilities.
Naive bayes using logistic regression's path. but no any learning process such as gradient descent. 

steps:-
0.preprocess:
1.lowercase,removals,tokenize,stemming
2.counts-using conditional probabilities
3.Laplacian Smoothening
4.Loglikelihood-Lambda ,to set a word neutral or...word sentiment
5.using this, add all word sentiment, to get sentence sentiment...log likelihood
6.>0......positive
7.<0......negative


Training: Naive bayes classifier,
1.getting annotated dataset. pos/neg
2.preprocess: to [w1,w2,w3,..] by lowecase,removals stopwords,punctuations,urls,tags etc,followed by stemming,tokenization..
3.compute frequency: freq(w,class)
4.get p(w/pos),p(w/neg)
5.get loglikelihood, lambda=log(p(w/pos)/p(w/neg))
6.get logprior=log(n(pos)/n(neg))........balanced or not....logprior=0 if balanced.
