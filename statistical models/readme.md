
**Statistical models** can be widely divided into **discriminative** and **generative** models. Discriminative models leverage conditional probability distributions while generative ones leverage non-conditional (joint) distributions.

<img width="232" alt="mod" src="https://github.com/ranja-sarkar/stats/assets/101544669/64651d9a-486f-49ae-91a9-7b3749bdf42b">


Example -

Discriminative classifiers assume a functional form of P(y|X) and estimate the parameters from input data.

P(X) == prior probability

P(y) == marginal probability

Generative classifiers estimate parameters from the data given a likelihood function and use the Bayes’ theorem to calculate the posterior probability.

