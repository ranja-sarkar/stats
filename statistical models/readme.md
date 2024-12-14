
All **statistical models** can be widely divided into **discriminative** and **generative** models. Discriminative models leverage **conditional probability distributions** while generative ones leverage **non-conditional (joint) distributions**. 

<img width="232" alt="mod" src="https://github.com/ranja-sarkar/stats/assets/101544669/64651d9a-486f-49ae-91a9-7b3749bdf42b">

What is learned with a discriminative algorithm is the decision boundary, dividing the data space. What is learned with a generative algorithm is the probability distribution of data. 

<img width="444" alt="2" src="https://github.com/user-attachments/assets/e1cb3a96-2102-4a12-9e78-c8969f56a5e1" />


Probability modeling involves the quantification of tendencies and usually addresses real project goals. There are 2 general ways to build statistical models viz., 

**i) model-based approach**, where the parameters of interest are intended to capture important and interpretable features of the generating process, separated from the (accidental) features of the particular data,

**ii) design-based approach**, where the probability calculations are based on the randomization used in the investigation/experiment. 

**The fundamentals of Bayes theorem have no opinion on which way is utilized, and can be used in both the approaches.**

For more, please read this book chapter: https://bayesiancomputationbook.com/markdown/chp_09.html

In unsupervised learning and/or supervised learning or in general in a statistical analysis, the most influential factor is the driving question which we try to answer with our analysis.

Improving statistical inferences by asking the right statistical question: https://lakens.github.io/statistical_inferences/05-questions.html


**Discriminative models** assume a functional form of P(y|X) and estimate the response from the data using this function. **Logistic regression** (supervised machine learning) is perhaps the best example of a discriminative model. Logistic regression can be considered as the linear regression of classification models. While linear regression is used to predict a continuous dependent variable (target), logistic regression discriminates between two or more classes of the target. **Support Vector Machine (SVM)** is another example. SVM has applications in both regression and classification problems. An n-dimensional space containing datapoints is divided into classes using support vectors, and the decision boundary is called a hyperplane. Other examples of discriminative models are kNN, random forest. 

These models are also effective for (supervised) deep learning tasks like CNNs (image recognition, computer vision) and RNNs (time-series analysis, NLP).  

**Generative models** estimate parameters from the data given a likelihood function and use the Bayes’ theorem to calculate the posterior probability (see formula below). **GAN** is a generative model which uses two submodels, the generative submodel/subnetwork generates new data points (new probability distribution) and the discriminator subnetwork classifies them into real or fake. Another example is **Bayesian Network** which uses a directed acyclic graph (DAG) to draw (probabilistic) inferences. Some other examples are Naive Bayes, hidden Markov Model (HMM), LDA (latent Dirichlet allocation). 

These models understand how data is embedded in space. Autoencoder, Boltzmann machine, and self-organizing maps are some (unsupervised) deep learning algorithms which make use of generative models for tasks like exploratory data analysis of high dimensional datasets, image denoising, image compression, anomaly detection and generating new images.

