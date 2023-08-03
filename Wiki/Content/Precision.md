Created: 2022-11-02 20:11:09
Tags: #ML #DataScience #classification_metric #ml_metrics

>[!WARNING]
>For understanding precision score you need to read [[Confusion Matrix]] note firstly.
## Note
*Precision* uses to evaluate classification [[machine learning]] algorithm. It has more stability with imbalanced data then [[Accuracy score]].
![[Precisionrecall.svg.png|400]]
### Definition
- *Precision* is the fraction of relevant instances among the [[retrieve|retrieved]] instances. In other words ==how many [[retrieve|retrieved]] samples are relevant?==.
$$Precision = \frac{TP}{TP + FP}$$
### Probabilistic interpretation
- ==*Precision* is the estimated probability that a document randomly selected from the pool of [[retrieve|retrieved]] documents are relevant.==
>[!INFO]
>Relevant element (document) is the element (document) has a positive class label.

### Advantages 
- Good works with imbalanced data
- Easy interpretable

## Related metrics
- [[Recall]]
- [[F measure]]
- [[Accuracy score]]
- [[Balanced accuracy score]]

## References
- [Precision and recall from Wikipedia](https://en.wikipedia.org/wiki/Precision_and_recall)
## Zero Links
- [[Classification Metrics]]