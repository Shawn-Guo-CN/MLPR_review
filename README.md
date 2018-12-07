# "A" Review of MLPR (2018)

### COMMENTS
All the following contents are my personal opinions.
I'm very glad to share these knowledge and I would really 
appreciate that if you could give any comments on them.

## Outline

### What is a machine learning system}

The diagram of a machine learning (ML) system is given in the figure as follow.

![Figure: Diagram of ML systems.](pic/ml_system.png)



### Key questions in ML system

In this review, we mainly focus on the following questions in ML systems:

 - How to represent and extract features from samples $\mathbf{x}$;
 - What different kinds of models could be for different types of labels $\mathbf{y}$;
 - How to get best parameters $\mathbf{w}$ for a model;
 - How to choose among different models.

### Represent and extract features from $\mathbf{x}$

How to represent $\mathbf{x}$:

 - original $\mathbf{x}$;
 - basis function expansion:
    - radial basis functions;
    - gaussian distribution;

How to extract feature:
 - autoencoder \& PCA;
 - neural networks;
 - gaussian processes;
 - kernel tricks;

### Different Models for different kinds of $\mathbf{y}$: regression \& classification

Types of labels and corresponding models:
 - for continuous $\mathbf{y}$: regression
   - linear regression;
 - for discrete $\mathbf{y}$: classification
   - logistic regression;

### Different methods for getting best parameters for a model
 - analytical solution:
   - for linear regression
 - numerical solution:
   - gradient descent \& cost funciton;
   - Estimation-Maximization algorithm;
   - laplace approximations;
   - variational method \& KL divergence;
 - regularization:
   - L1
   - L2
   - early stopping

### Choosing a model among models

 - held-out validation
 - bayesian inference
   - variational inference
