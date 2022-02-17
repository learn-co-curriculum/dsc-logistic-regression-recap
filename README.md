# Logistic Regression - Recap

## Introduction

Well done! In this section you learned about a different supervised learning technique: classification.

You also reviewed maximum likelihood estimation and saw how it applies to logistic regression. This included writing some challenging code, including gradient descent, which pushed you to think critically regarding algorithm implementation.

## Logistic Regression

Specifically, you practiced building a very basic classification model from scratch - a logistic regression model. Logistic regression uses a sigmoid function which helps to plot an "s"-like curve that enables a linear function to act as a binary classifier.

## Log-likelihoods in Maximum Likelihood Estimation

One of the nuances you saw in maximum likelihood estimation was that of log-likelihoods. Recall that the purpose of taking log-likelihoods as opposed to likelihoods themselves is that it allows us to decompose the product of probabilities as sums of log probabilities. Analytically, this is essential to calculating subsequent gradients in order to find the next steps for our optimization algorithm.


## Local Minima in Gradient Descent

One of the most important notes from this section is that **gradient descent does not guarantee an optimal solution**. Gradient descent is meant to find optimal solutions, but it only guarantees a local minimum. For this reason, gradient descent is frequently run multiple times, and the parameters with the lowest loss function then being selected for the final model.


## Summary

This section was designed to give you additional practice coding algorithms in Python, and a deeper understanding of how iterative algorithms such as logistic regression converge to produce underlying model parameters.
