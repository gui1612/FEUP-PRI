# IR Concepts

#### What is… a document, a collection, a term, a bag of words?

###### Document
A document is whatever unit we have decided to build a retrieval system over.

A document can be web pages, email messages, books, news articles, research paper, and so on...

A document must contain significant text content and some sort of structure (e.g.: title, body, date, tags, author)

###### Collection

A collection is a group of documents.

###### Term

Terms are indexed units. They are included in the IR's dictionary.

###### Bag of Words
A Bag of Words (BoW) representens text as an unordered collection of words, disregarding grammar and word order. BoW simplifies text into term frequency counts for each document.

#### Define stemming.
Stemming is the process of reducing inflected (or sometimes derived) words to their *word stem*, base or root form (e.g.: "jumping" -> "jump")


#### What is… an inverted index, a vocabulary, a postings list?

Doing a term-document matrix is very naive and the more documents our collection has, the more expensive it gets. We will notice however that this matrix is very sparse.

We keep a dictionary of terms (**vocabulary**).

Having this said, a much better representation would be to store the term and the documents when it occurs (the **postings list** or inverted list)


#### What is… an information need, a query, a results list?

###### Information need

An **information need** is the topic about which the user desires to know more.

E.g.: "Information on whether drinking red wine is more effective at reducing your risk of heart attacks than drinking white wine"

###### Query

A query is what the user conveys to the computer in an attempt to communicate the information need.

E.g.: [win red white heart attack effective]

###### Results List

A results list is the set of documents or items retrieved by an IR system in responde to a user's query. It consists of items that the system deems relevant to the user's information need based on the search terms provided.


#### What is a relevant result in a results list?

A result is relevant if it is one that the user perceives as containing information of value with respect to their personal information need,