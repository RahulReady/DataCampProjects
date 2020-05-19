# Movie Similarity from Plot Summaries
## Motivation
Who doesn't like watching movies? Based on plot summaries for movies, can we find the movies that are the most similar? If someone really liked, _Braveheart_ they would probably like _Gladiatior_  (one of the results of this project!).

## Topics Covered

* **Tokenization:** Breaking down texts into individual statements or words.
* **Stemming:** Converting words into its base root form. 
* **Tfidf Vectorizer:** Converts docs to tf-idf features. Similar to count but normalizes based on corpus/ docs
* **Similarity Distance:** 1 - cosine similarity angle. Cosine similarity is calculating the cosine angle between 2 vectors. The more similar, the higher the cosine angle.
* **Dendrograms:** Tree like diagram to visualize the closest similarity between indepedent variables. In this case, movies. The lower the linkage between movies, the more similar the movies are.


## Steps taken

1. Import and understand the movie dataset.
2. Combine wiki plot and imdb data.
3. Tokenize and step movie plots
4. Create a tf-idf vectorizer to transform the tokenized and stemmed words into a matrix
5. Calculate cosine similarity distances between movies.
6. Create a dendrogram from the similarity distances
