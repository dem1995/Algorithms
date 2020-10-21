Work in Progress
# Dataset Holdouts - Splitting datasets for learning and evaluation
## Introduction/Overview
## Overfitting
TODO. Maybe use example from https://stats.stackexchange.com/questions/128616/whats-a-real-world-example-of-overfitting#:~:text=The%20analysis%20that%20may%20have%20contributed%20to%20the,size%2C%20given%20the%20observed%20frequency%20of%20%22lesser%22%20earthquakes.?

You're unlikely to forget what overfitting is (or so you're telling yourself at the moment), so skipping this for now.

## Training-(Validation)-Testing
Used in order to avoid overfitting. Break up your dataset into a training set (

## Cross-Validation
### Description
Repeatedly take a portion ("fold") of the 


## Bootstrapping
### Description
From Wikipedia: As an example, assume we are interested in the average (or mean) height of people worldwide. We cannot measure all the people in the global population, so instead we sample only a tiny part of it, and measure that. Assume the sample is of size *N*; that is, we measure the heights of *N* individuals. From that single sample, only one estimate of the mean can be obtained. In order to reason about the population, we need some sense of the variability of the mean that we have computed. The simplest bootstrap method involves taking the original data set of heights, and, using a computer, sampling from it to form a new sample (called a 'resample' or bootstrap sample) that is also of size *N*. The bootstrap sample is taken from the original by using sampling with replacement (e.g. we might 'resample' 5 times from [1,2,3,4,5] and get [2,5,4,4,1]), so, assuming *N* is sufficiently large, for all practical purposes there is virtually zero probability that it will be identical to the original "real" sample. This process is repeated a large number of times (typically 1,000 or 10,000 times), and for each of these bootstrap samples we compute its mean (each of these are called bootstrap estimates). We now can create a histogram of bootstrap means. This histogram provides an estimate of the shape of the distribution of the sample mean from which we can answer questions about how much the mean varies across samples. (The method here, described for the mean, can be applied to almost any other statistic or estimator.)
### Counts
~300 fits, rule of thumb <https://stats.stackexchange.com/a/14550>

