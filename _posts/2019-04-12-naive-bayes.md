---
layout: post
title:  "Few words about Naïve Bayes classifier. Uhmm... hmm..."
date:   2019-04-12 23:13:20
---

*I write this article in order to better understand commonly used machine learning algorithms*

![cover image](https://akinariobi.github.io/assets/img/naive-bayes/1.png)

Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Naive Bayes is a probabilistic machine learning algorithm that can be used in a wide variety of classification tasks. Typical applications include filtering spam, classifying documents, sentiment prediction etc.


#### Is it really naïve?

The name naive is used because it assumes the features that go into the model is independent
of each other. That is changing the value of one feature, does not directly influence
 or change the value of any of the other features used in the algorithm.
For example, if we're trying to analyze the sentence we assume that every word in a sentence is independent of the other ones. This means that we’re no longer looking at entire sentences, but rather at individual words. So for our purposes, “I like learning maths” is the same as “maths like learning I” and “I maths like learning”.

#### Formula

* P(A/B): the probability of hypothesis A given the data B. This is known as posterior probability.
* P(B/A): the probability of data B given that the hypothesis A was true. This is known as posterior probability.
* P(A): the probability of hypothesis A being true (regardless of the data). This is known as the prior probability of A.
* P(B): the probability of the data (regardless of the hypothesis). This is known as the prior probability.


[wco]: http://www.wcoomd.org/en/topics/facilitation/instrument-and-tools/tools/single-window-guidelines.aspx
