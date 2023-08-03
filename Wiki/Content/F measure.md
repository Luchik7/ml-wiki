Created: 2022-11-02 22:11:63
Tags: #ML #DataScience #classification_metric #ml_metrics
>[!WARNING]
>For understanding this metrics, you need to know what is [[Precision]] and [[Recall]] firstly

## Note
*F measure* combines [[Precision]] and [[Recall]] together. We can define it as harmonic mean of [[Precision]] and [[Recall]].

Traditional or **balanced** *F measure* defines as:
$$F_1= 2 * \frac{precision * recall}{precision + recall} = \frac{2TP}{2TP + FP + FN}$$
But in **general case** we can define *F measure* as:
$$F_{\beta}=(1 + \beta^2) * \frac{precision * recall}{\beta^2 * precision + recall} = \frac{(1 + \beta^2)TP}{(1 + \beta^2)TP + \beta^2FN + FP}$$
>[!NOTE]
>There is three commonly used values for $\beta$ parameter:
> - Use $F_1$ ($\beta=1$) if you need to have balance between [[Precision]] and [[Recall]];
> - Use $F_2$ ($\beta=2$) if [[Recall]] value is more important than [[Precision]] (weights recall higher than precision);
> - Use $F_{0.5}$ ($\beta=0.5$) if [[Precision]] value is more important than [[Recall]] (weights precision higher than recall).

## Related metrics
- [[Recall]]
- [[F measure]]
- [[Accuracy score]]
- [[Balanced accuracy score]]

## References
- [F-score Wikipedia](https://en.wikipedia.org/wiki/F-score)

## Zero Links
- [[Classification Metrics]]