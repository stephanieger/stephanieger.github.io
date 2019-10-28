---
layout: default
---


# About Me

I'm a sixth year Applied Mathematics graduate student at Northwestern University. My work has mainly focused on deep learning classification algorithms for temporal data. Much of my recent work has been focused on developing extensions of neural network architectures to complex temporal datasets. 

In addition to my work in machine learning, I'm involved with Northwestern Splash, an educational outreach program where college students teach one off classes to local high school students on topics that range from cryptography to german wheel to east coast swing. Our program is supported by the Learning Unlimited, the national umbrella organization. 

# Current Research Focus

## Imbalanced Multivariate Sequence Classification

It is known that standard machine learning methods perform poorly when the dataset is imbalanced. For example, if we're predicting if an image is a dog or a cat, and 99% of the training set is composed of cat images, a model is unlikely to learn what a dog looks like. Techniques that are used for imbalanced datasets generally involve oversampling the minority data, ensembling the data, or generating synthetic minority data to supplement the training set. While methods exist for oversampling timeseries data, these methods are not suited for multivariate temporal data as these methods cannot account for correlations between features at different timesteps. We developed a Generative Adversarial Network based method for generating synthetic minority data for multivariate temporal data. This method significantly improve model classification accuracy. 

[Autoencoders and Generative Adversarial Networks for Imbalanced Sequence Classification](https://arxiv.org/abs/1901.02514)

## Explainability of Recurrent Neural Networks (RNNs)

Neural network models  have been shown to outperform standard machine learning methods on many classification tasks. However, they lack the transparency of standard classification methods such as decision trees. I am interested in comparing general explainability methods to RNN specific methods in order to determine which features that are important for model classification. This project is supported by an industry partner.

## Set Based Models

Neural network architectures have been developed for timeseries classification. These include LSTMs, GRUs, and transformers. I am interested in understanding how these models can be used when considering a list of input data with no inherent order. This project is supported by an industry partner.
