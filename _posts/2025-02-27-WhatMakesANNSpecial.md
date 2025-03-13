---
layout: post
title: What makes neural nets special?
categories: machinelearning
comments: true
---

While we are awed by the power of LLMs and all the exciting possibilities they bring, it's worth taking a step back to ask: what actually powers these LLMs, and what makes them special? We know that neural networks (Artificial Neural Networks or ANNs, to be precise) are behind the LLM prowess, but what makes ANNs so powerful? Machine Learning practitioners would already know this, but the secret sauce is the _Universal Approximation Theorem_.
This theorem essentially states that even a shallow ANN can approximate any continuous mathematical function. Let that sink in for a moment. If we make the ANN deeper, the approximation gets closer to the actual function. 

I found two valuable resources for understanding this theorem:

* [Universal Approximation Theorem](https://www.deep-mind.org/2023/03/26/the-universal-approximation-theorem/#Universal_Approximation_Theorem)
* [A visual proof that neural nets can compute any function](http://neuralnetworksanddeeplearning.com/chap4.html)

I'll admit that I'm still working to understand all the mathematics behind this theorem, but the notebook (approximating the sine function) accompanying the DeepMind blog post and the visual proof in Michael Nielsen’s blog post are very useful in building intuition and demonstrating the power of a simple ANN. I highly recommend spending some time with both these resources.