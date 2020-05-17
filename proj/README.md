# Predict Blood Donations
## Motivation
According to WebMD, 5 million Americans need need a blood transfusion every year (clearly an important issue). We will analyze data recorded by a Taiwanese blood transfusion service center as to whether or not a person will donate blood if the mobile clinic comes back.  

## Topics Covered

* **RFM analysis:** Recency, Frequency, and Monetary value. A way to gauge customer value.
* **Shell to Interact with data:**
* **TPOT:** Python automated ML tool to optimize for searching ML pipelines
* **Log Normalizing data:** Essentially lowering the variance of data that is far apart through log transforms.

## Steps taken

1. Data understanding
2. Data preprocessing including checking data cleanliness.
3. Check how 'balanced' the dataset is.
4. Splitting the data into train and test accounting for data imbalance
5. Use TPOT to select a baseline model
6. Check and account for large variances using log normalization
7. Train a new model
8. Make a conclusion
