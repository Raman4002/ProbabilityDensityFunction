# Species Prediction using Petal Length Analysis

## Introduction
In our attempt to predict the species of a plant based on its petal length, we initially explored the distribution characteristics by drawing a histogram. The examination revealed a non-normal distribution of petal lengths, prompting us to employ kernel density estimation (KDE) techniques for a more nuanced analysis.

## Kernel Density Estimation
After conducting a comprehensive analysis of various kernel density plots, we arrived at the following key conclusions:

### a) Setosa Prediction
Any petal length below 2.2 can be confidently classified as Setosa. This assertion is grounded in the fact that 100% of Setosa data points have a length below 2.2.

### b) Versicolor Prediction
Petal lengths above 2.2 and below 4.7 are indicative of Versicolor. This prediction holds with a high level of confidence, as 92% of Versicolor data points fall below the 4.7 length threshold.

### c) Virginica Prediction
Petal lengths exceeding 4.7 are attributed to the Virginica species.

### d) Feature Distinction
Remarkably, apart from petal length, no other attribute provides a clear demarcation between different species. The kernel density plots of alternative attributes exhibit significant overlap, making petal length a crucial factor in species prediction.

These findings contribute valuable insights into leveraging petal length for accurate species classification, underscoring the importance of considering distribution characteristics in predictive modeling.
