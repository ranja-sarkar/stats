# statistics

The **law of large numbers** is a mathematical law - the average of the results obtained from a large number of independent random samples converges to the true value, if it exists. 
More formally, the **law of large numbers** states that given a sample of independent identically distributed (iid) values, the sample mean converges to the true mean.
The **law of large numbers** applies to the average of the results obtained from repeated (large number of) trials and claims that this average converges to the expected value.


✔ **Accuracy** and **precision** cannot be used interchangeably, the former being true to intention (degree of closeness of measured value to true value) while the latter is true to itself (degree of closeness of repeated measured values)

✔ **Probability** and **likelihood** are different terms; the former is finding the chance of outcomes given a data distribution, the latter is finding the most likely distribution given the outcomes. 


**DESCRIPTIVE STATISTICS**: For inference of (smaller) sample data

**INFERENTIAL STATISTICS**: For inference of (larger) population

**CENTRAL LIMIT THEOREM**
The central limit theorem (CLT) states that, given a sufficiently large sample size, the sampling distribution of the mean for a variable approximates a normal distribution regardless of that variable’s distribution in the population.

CLT is vital for two reasons — the normality assumption and the precision of the estimates.

The normality assumption is vital for parametric hypothesis tests of the mean. Consequently, you might think that these tests are not valid when the data are non-normally distributed. However, if your sample size is large enough, CLT kicks in and produces sampling distributions that approximate a normal distribution. This fact allows you to use these hypothesis tests even when your data are non-normally distributed as long as your sample size is large enough.

The 'precision of estimates' property of CLT becomes relevant when using a sample to estimate the mean of an entire population. With a larger sample size, your sample mean is more likely to be close to the real population mean. In other words, your estimate is more precise.

**STATISTICAL TESTS**:

Depending on your goal and the data, you select a **test**.

If the goal is to quantify an association between two groups, we check **Pearson correlation** for parametric data, **Spearman correlation** for non-parametric data.
If the goal is to predict a target from one or more variables, we perform **simple regression** (two variables) and **multiple regression** (more than two variables) for parametric data. 
If we have to compare unpaired (independent) groups, we perform unpaired **T-test** (or one-way **ANOVA** for 2+ groups) for parametric data, and **Mann-Whitney test** (2 groups) for non-parametric data. 

**Parametric test**:-

Assumption: Data has normal distribution 

<https://en.wikipedia.org/wiki/Normal_distribution>

![image](https://user-images.githubusercontent.com/101544669/172365078-9c820e5f-6a23-4d56-acc3-2ee9df161792.png)


**Non-parametric test**:-

No assumption

![image](https://user-images.githubusercontent.com/101544669/172365175-8491678c-50f7-452b-897c-eecbb7111739.png)


Depending on datatypes and number of samples, a **hypothesis test** is carried out. 

Traditional testing is called non-Bayesian. It is how often an outcome happens over repeated runs (repeat sampling) of the experiment. It’s an objective view of whether an experiment is repeatable. 

**Bayesian hypothesis testing** is a subjective view of the same - it takes into account how much faith you have in your results. It includes prior knowledge about the data and personal beliefs about the results.


<img width="493" alt="0" src="https://github.com/ranja-sarkar/stats/assets/101544669/d947dc46-e799-4647-af50-2da545412af9">

For more: https://en.wikipedia.org/wiki/F-test
          https://en.wikipedia.org/wiki/Analysis_of_variance


**Data classification** based on privacy, security, risk management and regulatory compliance:-
- public
- confidential
- restricted
- internal 

**MEASURES OF CENTRAL TENDENCY**
![data](https://user-images.githubusercontent.com/101544669/172350887-e9527614-3737-4ad0-99af-868333c2f6aa.png)

![image](https://user-images.githubusercontent.com/101544669/172351517-74e016c6-709e-47b4-bf01-299afad8e25f.png)

**Mode**:  Number that occurs most often in a dataset.

**Median**: Middle number/value when a dataset is ordered from least to greatest.

![image](https://user-images.githubusercontent.com/101544669/172351874-c889ca8b-c52b-493d-bebe-9e19ca12820e.png)

![image](https://user-images.githubusercontent.com/101544669/172352049-a691a986-560c-42fe-bae3-cd4fa899a38f.png)

Read more on the first 4 moments - mean, variance, skewness, and kurtosis from this excellent blog post: https://gregorygundersen.com/blog/2020/04/11/moments/


A violin plot shows the shape (density distribution) of data which boxplot does not, and it must be used to explore skewed data. 

https://plotly.com/python/violin/


<img width="214" alt="vp" src="https://github.com/ranja-sarkar/stats/assets/101544669/eb349bbc-acf3-47e8-ab49-dea45666401e">


There are **power transformations** that variables need to undergo if they follow either right-skewed or left-skewed distributions. Parametric machine learning models like linear regression assume real-valued variables in the input data have Gaussian distributions. Non-parametric models like kNN do not have this assumption, yet often are more reliable and perform better when the input variables have Gaussian distributions. As such, variables with skewed distributions (Gaussian-like) or different distributions altogether need transformation. Power transforms refer to a class of techniques utilizing a power function (like logarithm or exponent) to make the probability distribution of a variable Gaussian. 

Gaussian (normal) distribution: https://ranjas.substack.com/p/why-the-gaussian

There're 2 popular approaches for automatic power transforms:

•	Box-Cox Transform
•	Yeo-Johnson Transform 

They find a parameter (lambda) that best transforms a variable for example, lambda = -1 is a reciprocal transform, lambda = 0 is a log transform, lambda = 0.5 is a square root transform.


**MEASURES OF DISPERSION**: Range, quartile deviation and interquartile range (quartile deviation is half of the interquartile range),
			variance, standard deviation
			
![image](https://user-images.githubusercontent.com/101544669/172353525-d1b2bcf0-ff6c-42bc-99e6-db6c3edb1e2f.png)

![image](https://user-images.githubusercontent.com/101544669/172354301-b62ea3b6-bc64-4f8f-bc65-58cb7b5d5f90.png)

✅It's mentionworthy that the **standard error** (SE) of a sample mean is an estimate of how far the mean is likely to be away from the population mean, whereas the **standard deviation** (SD) of the sample is the degree to which individuals within the sample differ from the mean. 

For more on SE: https://en.wikipedia.org/wiki/Standard_error

**COVARIANCE & CORRELATION**:

![image](https://user-images.githubusercontent.com/101544669/172354401-9403bc08-05e5-4316-9174-39aaf0ef1eab.png)

![image](https://user-images.githubusercontent.com/101544669/172354769-82567b68-536e-449a-9733-3e1b4ab6c90c.png)




