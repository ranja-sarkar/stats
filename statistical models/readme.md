



**Discriminative models** assume a functional form of P(y|X) and estimate the response from the data using this function. **Logistic regression** (supervised machine learning) is perhaps the best example of a discriminative model. Logistic regression can be considered as the linear regression of classification models. While linear regression is used to predict a continuous dependent variable (target), logistic regression discriminates between two or more classes of the target. **Support Vector Machine (SVM)** is another example. SVM has applications in both regression and classification problems. An n-dimensional space containing datapoints is divided into classes using support vectors, and the decision boundary is called a hyperplane. Other examples of discriminative models are kNN, random forest. These models are also effective for (supervised) deep learning tasks like CNNs (image recognition, computer vision) and RNNs (time-series analysis, NLP).  

**Generative models** estimate parameters from the data given a likelihood and use the Bayes’ theorem to calculate the posterior probability (see formula below). **Generative Adversarial Network (GAN)** is a generative model which uses two submodels, the generative subnetwork generates new data points (new probability distribution) and the discriminator subnetwork classifies them into real or fake. 

<img width="455" alt="bb" src="https://github.com/user-attachments/assets/ddc7ca65-9e17-4608-9e86-ac6ae5683818" />


Another example is **Bayesian Network** which uses a directed acyclic graph (DAG) to draw (probabilistic) inferences. Some others are Naive Bayes, hidden Markov Model (HMM), LDA (latent Dirichlet allocation). These models understand how data is embedded in space. Autoencoder, Boltzmann machine, and self-organizing maps are some (unsupervised) deep learning algorithms which make use of generative models for tasks like exploratory analysis of high dimensional datasets, image denoising, image compression, anomaly detection, and generating images.


