# Reducing Traffic Mortality
## Motivation
How can we use data to help reduce traffic mortality? Are some states more prone to fatalities than others? How can we cluster traits with similar mortality types? What actionable insights can we derive from data provided by the US department of transportation? These are some of the many questions this project tries to answer.

## Topics Covered

* **Basic linux command:s** !pwd, !ls, !head -n10
* **Pairplots:** Way to graph scatterplot data/ histograms between the feature variables.
* **Pearson Correlation:** Quantifying the strength of linear relationship between variables.
* **Multi-variate linear regression:** Measure how strongly the feature variables correspond to the output variable.
* **Masking Relationship:** For ex. the regression coefficent of A is positive, but the correlation coefficient is negative.
* **Principal Component Analysis:** Reducing the number of features to only the 'most important' features. This is done by keeping features that account for the most variance of the entire data.
* **Scaling data:** Converting the range of values for each numeric feature to between 0 and 1.
* **K-means clustering:** An unsupervised learning technique to divide data into k groups.


## Steps taken

1. Understand data by reading the files and getting an overall 'sense' of the data.
2. Perform preliminary EDA such as correlations and pairplots.
3. Fit a multivariate linear regression model
4. Perform PCA and visualize the principal components
5. Visualize the clustered data group using K-means
6. Group the sum, mean, counts of fatalities by the cluster groups to determine which cluster to look into further.
