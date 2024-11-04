
**Statistical models** can be widely divided into **discriminative** and **generative** models. Discriminative models leverage conditional probability distributions while generative ones leverage non-conditional (joint) distributions.

<img width="232" alt="mod" src="https://github.com/ranja-sarkar/stats/assets/101544669/64651d9a-486f-49ae-91a9-7b3749bdf42b">

What's learned with a discriminative algorithm is the decision boundary (L) dividing the data space. 
What's learned With a generative algorithm is the probability distribution of data (R). See below figures. 

<img width="385" alt="5" src="https://github.com/user-attachments/assets/bcf6bbba-3972-4d52-aec1-613f4b3b85fc">


**Examples** of the statistical models:

<img width="394" alt="1" src="https://github.com/user-attachments/assets/01e70faa-ae86-4a16-aee8-f63632fe1264">


**Discriminative models** assume a functional form of P(y|X) and estimate the parameters from input data.

P(X) and P(y) are known as prior probability and marginal probability.

<img width="477" alt="1" src="https://github.com/user-attachments/assets/0e6c1caa-c628-4be6-b34f-7bf3b06402b4">

Discriminative models are also effective for (supervised) deep learning tasks like CNNs (image recognition, computer vision) and RNNs (time-series analysis, NLP).  

**Generative models** estimate parameters from the data given a likelihood function and use the Bayes’ theorem to calculate the posterior probability.

<img width="457" alt="2" src="https://github.com/user-attachments/assets/9a9974e9-ae88-400d-b40e-ca7269dbe3bb">

These models understand how data is embedded in space. Autoencoder, Boltzmann machine, and self-organizing maps are some (unsupervised) deep learning algorithms which make use of generative models for tasks like exploratory data analysis of high dimensional datasets, image denoising, image compression, anomaly detection and generating new images.

<img width="475" alt="3" src="https://github.com/user-attachments/assets/98bc8638-16c8-4589-8bb5-5fc35afe03b7">



