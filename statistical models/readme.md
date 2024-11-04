
**Statistical models** can be widely divided into **discriminative** and **generative** models. Discriminative models leverage conditional probability distributions while generative ones leverage non-conditional (joint) distributions.

<img width="232" alt="mod" src="https://github.com/ranja-sarkar/stats/assets/101544669/64651d9a-486f-49ae-91a9-7b3749bdf42b">

What's learned with a discriminative algorithm is the decision boundary and what's learned in a generative algorithm is the probability distribution of data.

<img width="385" alt="5" src="https://github.com/user-attachments/assets/bcf6bbba-3972-4d52-aec1-613f4b3b85fc">


Example ->

<img width="394" alt="1" src="https://github.com/user-attachments/assets/01e70faa-ae86-4a16-aee8-f63632fe1264">


Discriminative classifiers assume a functional form of P(y|X) and estimate the parameters from input data.

P(X) == prior probability

P(y) == marginal probability

Generative classifiers estimate parameters from the data given a likelihood function and use the Bayes’ theorem to calculate the posterior probability.

