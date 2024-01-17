# IR Tasks and Systems

#### What is the difference between information retrieval and data retrieval?

**Information Retrieval** is a field concerned with the structure, analysis, organization, storage, searching and retrieval of information.

IR is finding material (usually documents) of an unstructured nature (usually text) that satisfies an information need from within large collections (usually stored on computers)

**Data Retrieval** (a database management system / DBMS) works with structured data with well-defined semantics, whereas IR deals with unstructured/Semi-structured data. When a DBMS system is queried it returns exact/precise results or no results if no exact match is discovered. In contrast, querying an IR system yields several results with ranking. Small faults in information retrieval are likely to go unnoticed, but a single error object signifies total failure in data retrieval.

#### Give examples of IR and data retrieval systems.


#### Give some examples of retrieval tasks evaluated in TREC.

"**TREC** means Text Retrieval Conference. The U.S. National Institute of Standards and Technology (NIST) has run a large IR test bed evaluation series since 1992. Within this framework, there have been many tracks over a range of different test collections, but the best known test collections are the ones used for the TREC Ad Hoc track during the first 8 TREC evaluations between 1992 and 1999. In total, these test collections comprise 6 CDs containing 1.89 million documents (mainly, but not exclusively, newswire articles) and relevance judgements for 450 information needs, which are called topics and specified in detailed text passages. Individual test collections are defined over different subsets of this data. The early TRECs each consisted of 50 information needs, evaluated over different but overlapping sets of documents, TRECs 6-8 provide 150 information needs over about 528,000 newswire and Foreign Broadcast Information Service articles. This is probably the best subcollection to use in future work, because it is the largest and the topics are more consistent. Because the test documents are so large, there are no exhaustive relevance judgements. Rather, NIST assessors' relevance judgments are available only for the documents that were among the top k returned for some system which was entered in the TREC evaluation for which the information need was developed."

Some examples of retrieval tasks evaluated in TREC are:

- Ad Hoc Retrieval
- Filtering Tasks
- Question Answering (QA)
- Cross-Language Retrieval
- Web Retrieval
- ...


#### What are the modules of an IR system?

