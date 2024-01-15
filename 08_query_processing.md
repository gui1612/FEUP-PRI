# Query Processing

#### Describe and distinguish between the two query processing techniques — document-at-a-time and term-at-a-time.

**Document-at-a-time** calculates complete scores for documents by processing all term lists, one document at a time. At the end, all documents are sorted according to their score.

**Term-at-a-time** accumulates scores for documents by processing term lists one at a time. When all terms are processed, the accumulators contain the final scores of all matching documents.


#### In what contexts is query transformation / expansion advantageous?

With **query expansion**, user give additional input on query words or phrases to suggest additional terms. Users opt to use one of alternative query suggestions.




#### What techniques can be used to apply transformations / expansions to user queries?

- Use synonyms and related words from a global thesaurus.
    - Use a controlled vocabulary to build a thesaurus;
    - Use a manual thesaurus built by editors;
    - Automatically derive thesaurus, e.g. use text statistics;
    - Use query log mining to find related expansions (global, contextual, user-based);


#### Identify and describe query expansions techniques, such as relevance feedback or pseudo-relevance feedback.

###### Relevance Feedback

- The idea of relevance feedback is to involve the user in the process to improve the final result set by considering user feedback about the initial set of results.

> Basic Procedure:

- The user issues a (short, simple) query.
- The system returns an initial set of retrieval results.
- The user marks some returned documents as relevant or non relevant.
- The system computes a better representation of the information need based on the user feedback.
- The system displays a revised set of retrieved results.

**Pseudo Relevance** feedback provides a method for automatic local analysis. It automates the manual part so that a relevance feedback algorithm is applied without extended user interaction.