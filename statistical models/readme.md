
All **statistical models** can be widely divided into **discriminative** and **generative** models. 

Discriminative models leverage **conditional probability distributions** while generative ones leverage **non-conditional (joint) distributions**.

Note: P(X) and P(y) are known as prior probability and marginal probability. 

<img width="232" alt="mod" src="https://github.com/ranja-sarkar/stats/assets/101544669/64651d9a-486f-49ae-91a9-7b3749bdf42b">

What is learned with a discriminative algorithm is the decision boundary, dividing the data space. 

What is learned With a generative algorithm is the probability distribution of data. 



"There are 2 general ways to build statistical models - 

**i) model-based approach**, where the parameters of interest are intended to capture important and interpretable features of the generating process, separated from the (accidental) features of the particular data,

**ii) design-based approach**, where the probability calculations are based on the randomization used in the investigation/experiment. 

The fundamentals of Bayes theorem have no opinion on which way is utilized and can be used in both the approaches."

For more, please read this book chapter: https://bayesiancomputationbook.com/markdown/chp_09.html

In unsupervised learning and/or supervised learning or in general, a statistical analysis, the most influential factor is the driving question which the one we try to answer with our analysis.

Improving statistical inferences by asking the right statistical question: https://lakens.github.io/statistical_inferences/05-questions.html



**Examples** of **statistical models**:

<img width="394" alt="1" src="https://github.com/user-attachments/assets/01e70faa-ae86-4a16-aee8-f63632fe1264">


**Discriminative models** assume a functional form of P(y|X) and estimate the parameters from input data.

<img width="477" alt="1" src="https://github.com/user-attachments/assets/0e6c1caa-c628-4be6-b34f-7bf3b06402b4">

Discriminative models are also effective for (supervised) deep learning tasks like CNNs (image recognition, computer vision) and RNNs (time-series analysis, NLP).  

**Generative models** estimate parameters from the data given a likelihood function and use the Bayes’ theorem to calculate the posterior probability.

<img width="457" alt="2" src="https://github.com/user-attachments/assets/9a9974e9-ae88-400d-b40e-ca7269dbe3bb">

These models understand how data is embedded in space. Autoencoder, Boltzmann machine, and self-organizing maps are some (unsupervised) deep learning algorithms which make use of generative models for tasks like exploratory data analysis of high dimensional datasets, image denoising, image compression, anomaly detection and generating new images.

<img width="475" alt="3" src="https://github.com/user-attachments/assets/98bc8638-16c8-4589-8bb5-5fc35afe03b7">

Probability modeling involves the quantification of tendencies and usually addresses the real project goals. Read more about it here:
https://www.fharrell.com/post/classification/


