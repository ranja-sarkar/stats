# stats
✔ **Accuracy** and **precision** cannot be used interchangeably, the former being true to intention (degree of closeness of measured value to true value) while the latter is true to itself (degree of closeness of repeated measured values)

✔ **Probability** and **likelihood** are different terms; the former is finding the chance of outcomes given a data distribution, the latter is finding the most likely distribution given the outcomes. 


**DESCRIPTIVE STATISTICS**: For inference of the smaller sample data

**INFERENTIAL STATISTICS**: For inference of the larger population

Depending on your goal and the datatype (parametric or non-parametric), you select a **test**.

If the goal is to quantify an association between two groups, we check **Pearson correlation** for parametric data, **Spearman correlation** for non-parametric data.
If the goal is to predict a target from one or more variables, we perform **simple regression** (two variables) and **multiple regression** (more than two variables) for parametric data. 
If we have to compare unpaired (independent) groups, we perform unpaired **T-test** (or one-way **ANOVA** for 2+ groups) for parametric data, and **Mann-Whitney test** (2 groups) for non-parametric data. 

**Parametric test**:-

Assumption: Data has normal distribution

![image](https://user-images.githubusercontent.com/101544669/172365078-9c820e5f-6a23-4d56-acc3-2ee9df161792.png)


**Non-parametric test**:-

No assumption

![image](https://user-images.githubusercontent.com/101544669/172365175-8491678c-50f7-452b-897c-eecbb7111739.png)


**HYPOTHESIS TESTS**: 
Depending on datatypes and data sample, hypothesis testing is carried out. 

<img width="493" alt="0" src="https://github.com/ranja-sarkar/stats/assets/101544669/d947dc46-e799-4647-af50-2da545412af9">

There's a data classification based on privacy, security, risk management and regulatory compliance: public, confidential, restricted and internal. 

For more: https://en.wikipedia.org/wiki/F-test
          https://en.wikipedia.org/wiki/Analysis_of_variance


**MEASURES OF CENTRAL TENDENCY**
![data](https://user-images.githubusercontent.com/101544669/172350887-e9527614-3737-4ad0-99af-868333c2f6aa.png)

![image](https://user-images.githubusercontent.com/101544669/172351517-74e016c6-709e-47b4-bf01-299afad8e25f.png)

![image](https://user-images.githubusercontent.com/101544669/172351874-c889ca8b-c52b-493d-bebe-9e19ca12820e.png)

![image](https://user-images.githubusercontent.com/101544669/172352049-a691a986-560c-42fe-bae3-cd4fa899a38f.png)

A violin plot shows the shape (density distribution) of data which boxplot does not, and it must be used to explore skewed data.

<img width="214" alt="vp" src="https://github.com/ranja-sarkar/stats/assets/101544669/eb349bbc-acf3-47e8-ab49-dea45666401e">


There are **power transformations** that variables need to undergo if they follow either right-skewed or left-skewed distributions.

**MEASURES OF DISPERSION**: Range, quartile deviation and interquartile range (quartile deviation is half of the interquartile range),
			variance, standard deviation
			
![image](https://user-images.githubusercontent.com/101544669/172353525-d1b2bcf0-ff6c-42bc-99e6-db6c3edb1e2f.png)

![image](https://user-images.githubusercontent.com/101544669/172354301-b62ea3b6-bc64-4f8f-bc65-58cb7b5d5f90.png)

![image](https://user-images.githubusercontent.com/101544669/172354401-9403bc08-05e5-4316-9174-39aaf0ef1eab.png)

![image](https://user-images.githubusercontent.com/101544669/172354769-82567b68-536e-449a-9733-3e1b4ab6c90c.png)

**Statistical models**:-

Discriminative (L) and Generative (R) (non-conditional)

<img width="232" alt="mod" src="https://github.com/ranja-sarkar/stats/assets/101544669/64651d9a-486f-49ae-91a9-7b3749bdf42b">




