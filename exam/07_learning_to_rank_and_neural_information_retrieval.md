# Learning to Rank and Neural Information Retrieval

#### What is Learning to Rank?

Learning to Rank is a task to automatically construct a ranking model using training data, such that the model can sort new objects according to their degrees of relevance, preference or importance.

- Learning to rank is the application of machine learning methods to information retrieval problems.


#### Which are the main approaches in LTR? How do they differ in terms of input and output data?

The main Learning to Rank approaches are:

###### Pointwise approach
- **Input:** feature vectors for single documents, e.g. scores for query-document pairs
- **Output:** relevance degree of each single document (e.g.: relevant/non-relevant)

###### Pairwise approach
- **Input:** pairs of documents, both represented as feature vectors.
    - Manually annotated data, e.g. (q,d,d') - d is more relevant to q than d' (harder to get, high quality)
    - Log data, e.g. if, for a query q, document d and d' are listed, and user clicked d and not d', then (q, d, d') can be inferred (easy, lower quality)
- **Output:** pairwise preferences (ranging from 1 to -1) between document pairs

###### Listwise approach
- **Input:** entire group of documents associated with a query, i.e. ranking lists.
    - Offline: obtain relevance judgements (q, d, s), where s is a score indicating the relevance of document d to query q.
    - Online: present different rankings to users (or interleave lists) and observe (from logs) which users prefer.
- **Output:** full document predicted ranking for query.

#### What is Neural Information Retrieval?

Neural Information Retrieval is the application of neural netweorks in the context of Information Retrieval tasks.

#### How can neural models be used in the retrieval process?

Neural Models improve retrieval by leveraging semantic matching, embeddings for document representation, learning to rank, personalization, context-awareness, question answering, content recommendation, and cross-modal retrieval. They enhance accuracy and relevance in search engines, recommendation systems and Information Retrieval by understanding semantics, learning from user behaviour and adapting to context.


#### What are document embeddings?

Document embeddings are compact, continuous representations that capture the semantic meaning of a document. They enable efficient comparison and retrieval of documents based on their content.


#### What is semantic search?

Semantic Search is a search technique that focuses on understanding the intent and context behind a user's query to provide more relevant search results by considering the meaning of words and the relationships between them, rather than just matching keywords.


#### What is the difference between Learning to Rank and Neural Information Retrieval?

**Learning to Rank (LTR)** is a broader approach that includes various algorithms, both traditional and neural, aimed at training models to rank search results based on relevance. **Neural Information Retrieval** specifically emphasizes the use of neural networks for tasks in Information Retrieval, encompassing document ranking, query understanding and relevance modelling within the context of search engines.

In essence, Neural IR is a subset of LTR that specifically leverages Neural Network techniques.