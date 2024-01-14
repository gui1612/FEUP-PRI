# Vector Model

#### What is the bag of words model for a document?
A Bag of Words (BoW) representens text as an unordered collection of words, disregarding grammar and word order. BoW simplifies text into term frequency counts for each document.

E.g.: 

If the document contained the sentence "'Good dog, good dog!', said the quick brown fow." 
The BoW representation would be 

```json
{
    "good": 2,
    "dog": 2,
    "said": 1,
    "the": 1,
    "quick": 1,
    "brown": 1,
    "fox": 1
}
```

Even though this method is simple, efficient and has built-in word independence, you will get loss of context, semantic gaps and sparsity using it. 


#### What is… term frequency, collection frequency, document frequency, inverse document frequency?


#### How do you calculate tf-idf weights?

TF-IDF (Term Frequency-Inverse Document Frequency) representation assigns a weight to each term in a document based on its frequency in the document and rarity across the entire corpus.

#### How do you rank documents in the vector model?

