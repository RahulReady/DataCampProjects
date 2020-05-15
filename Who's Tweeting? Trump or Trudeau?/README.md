# Tweet Classification
## Motivation
Trump is quite entertaining when it comes to tweets. Can we tell the difference between America's President and Canada's President?

## Topics Covered

* **Count Vectorizer:** Converts a collection of text docs to a matrix of token counts.
* **Tfidf Vectorizer:** Converts docs to tf-idf features. Similar to count but normalizes based on corpus/ docs
* **Multinomial Naive Bayes:** The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts. However, in practice, fractional counts such as tf-idf may also work.
* **Linear Support Vector Classifier:** Supervised Machine learning algo used for regression, classification and outlier detection.
* **Plotting Confusion Matrices:**


## Steps taken

1. Understanding the data
2. Transform Data by vectorizing tweets using countvectorizer and tfidf vectorizer.
3. Train two multinomial Nb model using both vectorizers and check accuracy
4. Evaluate model using confusion matrices
5. Train on linear support vector classifier and evaluate results
6. Check check feature (token) importance
7. Add your own tweet and have model give prediction
