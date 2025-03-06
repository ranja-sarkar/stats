
<img width="401" alt="sms" src="https://github.com/user-attachments/assets/b90edf97-2679-4e33-bbe8-30c0ef11f9d3" />


What is learned with a **discriminative algorithm** leveraging conditional probability distribution is the decision boundary, dividing the data space. 

What is learned with a **generative algorithm** leveraging joint probability distribution is the probability distribution of data. 

<img width="444" alt="2" src="https://github.com/user-attachments/assets/e1cb3a96-2102-4a12-9e78-c8969f56a5e1" />


Probability modeling involves the quantification of tendencies and there're 2 general ways to build statistical models viz., 

**i) model-based approach**, where the parameters of interest are intended to capture important and interpretable features of the generating process, separated from the (accidental) features of the particular dataset

**ii) design-based approach**, where the probability calculations are based on the randomization used in the investigation or experiment. 

**The fundamentals of Bayes theorem have no opinion on which way is utilized, and can be used in both the approaches.** To know more, please read this book chapter: https://bayesiancomputationbook.com/markdown/chp_09.html

<img width="108" alt="777" src="https://github.com/user-attachments/assets/8104de23-52a0-4716-ac39-79e3de7a6f93" />

The denominator in posterior (ratio) is the evidence/data available to us. 

In unsupervised and supervised learnings or in general in a statistical analysis, the most influential factor is the driving question which we try to answer with our analysis.

Improving statistical inferences by asking the right statistical question: https://lakens.github.io/statistical_inferences/05-questions.html

The two broad categories of statistical models - generative and discriminative actually tie back to the **two cultures of statistical modeling** explained in the paper:
https://github.com/ranja-sarkar/stats/blob/main/papers/breiman.pdf

**One culture assumes a given stochastic (non-deterministic) model generates data, and parameters are estimated from the data -> Data Model.** 

**The other culture treats data mechanism as unknown, and uses an algorithm to find a function that operates on predictors to estimate a response -> Algorithmic Model.**

**Discriminative models** assume a functional form of P(y|X) and estimate the response from the data using this function. **Logistic regression** (supervised machine learning) is perhaps the best example of a discriminative model. Logistic regression can be considered as the linear regression of classification models. While linear regression is used to predict a continuous dependent variable (target), logistic regression discriminates between two or more classes of the target. **Support Vector Machine (SVM)** is another example. SVM has applications in both regression and classification problems. An n-dimensional space containing datapoints is divided into classes using support vectors, and the decision boundary is called a hyperplane. Other examples of discriminative models are kNN, random forest. These models are also effective for (supervised) deep learning tasks like CNNs (image recognition, computer vision) and RNNs (time-series analysis, NLP).  

**Generative models** estimate parameters from the data given a likelihood and use the Bayes’ theorem to calculate the posterior probability (see formula below). **Generative Adversarial Network (GAN)** is a generative model which uses two submodels, the generative subnetwork generates new data points (new probability distribution) and the discriminator subnetwork classifies them into real or fake. 

<img width="455" alt="bb" src="https://github.com/user-attachments/assets/ddc7ca65-9e17-4608-9e86-ac6ae5683818" />


Another example is **Bayesian Network** which uses a directed acyclic graph (DAG) to draw (probabilistic) inferences. 

![DAG](https://github.com/user-attachments/assets/76849f9a-74c9-4680-b937-87b875622e34)


Some others are Naive Bayes, hidden Markov Model (HMM), LDA (latent Dirichlet allocation). These models understand how data is embedded in space. Autoencoder, Boltzmann machine, and self-organizing maps are some (unsupervised) deep learning algorithms which make use of generative models for tasks like exploratory analysis of high dimensional datasets, image denoising, image compression, anomaly detection, and generating new images.


