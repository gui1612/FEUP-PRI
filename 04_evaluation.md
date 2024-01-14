# Evaluation

# Evaluation

#### What is… precision, recall, interpolated precision?

###### Precision

**Precision** is the fraction of retrieved documents that are relevant:

```
Precision = #(relevant items retrieved) / #(retrieved items) = P(relevant|retrieved)
```

###### Recall

**Recall** is the fraction of relevant documents that are retrieved:

```
Recall = #(relevant items retrieved)/#(relevant items) = P(retrieved|relevant)
```

###### Extra

|               | Relevant             | NonRelevant          |
| ------------- | -------------------- | -------------------- |
| Retrieved     | True Positives (tp)  | False Positives (fp) |
| Not Retrieved | False Negatives (fn) | True Negatives (tn)  |

Then:

```
# Precision
P = tp / (tp + fp)

# Recall
R = tp / (tp + fn)
```

###### Interpolated Precision

The interpolated precision `p_interp` at a certain recall level `r` is defined as the highest precision found for any recall level `r' >= r`

#### What is… precision at k, R-precision?

###### Precision at k

###### R-Precision

#### Name the components of a test collection.

#### Why is a set of relevance judgements considered a “ground truth” for IR?

#### Draw a precision-recall curve for capturing the evolution of precision in the ranked list of results for a query.

#### What is an average 11-point precision-recall graph for a set of queries?

#### What is MAP, and do you calculate it for a set of queries in a test collection?
