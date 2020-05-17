# Charles Darwin Book Recommendations
## Motivation
Given that Darwin was quite a busy man, it would be interesting to see the types of books he wrote and read and compared how similar they are. If someone liked a certain book, this project would suggest other books that are closest in similarity to the selected book.

## Topics Covered

* **Glob:** Way to find pathname matching a specified pattern.
* **Corpus:** Collection of text.
* **Regular Expression:** Code standard to match a specific pattern. In this, we had to remove any non-alpha numeric characters.
* **Tokenize:** Transform each text into individual words.
* **Stemming:** Reducing a word to its base form. Ex: consignment, consigned, consigning all get transformed to consign.
* **Bag of Words:** Getting all unique occurrances of words and using it as features. (gensim corpora)


## Steps taken

1. Aggregating the text from the different books
2. Iterate through different books, remove non-alphanumeric text and append them into a list.
3. Tokenize each book
4. Stemming the tokenized corpus
5. Build a bag of words model with the stemmed tokens from each text
6. Find most common words in a given book.
7. Build a tf-idf model
8. Compute the distance between texts using cosine similarity and visualize it
