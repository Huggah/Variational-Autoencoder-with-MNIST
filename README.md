# Variational Autoencoder with MNIST
Using a variational autoencoder for unsupervised learning on MNIST digits.

## Real Images vs. Reconstructed Result
Real

![real](http://i65.tinypic.com/bhwy0l.jpg)

Reconstructed

![reconstructed](http://i63.tinypic.com/2le6hqx.jpg)

## Applied Bayesian Inference
A variational autoencoder consists of two parts: an encoder and a decoder. The encoder is given x and calculates the probability of z, expressed as a two-dimensional sample from a gaussian distribution. In other words, it approximates P(z|x). The decoder does the opposite, approximating the bernoulli distribution x which would be the input digit: P(x|z).

## Z given X plotted with X labels
![scatterplot](http://i68.tinypic.com/oaygjb.png)
