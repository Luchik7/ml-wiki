Created: 2022-11-01 13:11:07
Tags: #ML #DataScience #classification_metric #ml_metrics

## Note
***Accuracy*** is one of the metrics for classification model evaluation.

Informally, *accuracy* is a fraction of predictions our model got right:

$Accuracy = \frac{number\_of \_correct\_predictions}{total\_number\_predictions}$

Also, we can define *accuracy* in [[Confusion Matrix]] terms:

$Accuracy = \frac{TP + TN}{TP + TN + FP + FN}$

### Advantages 
- Easy for understanding
- Easy for calculation 

### Disadvantages 
- Works badly with imbalabced class problem. For imbalanced classes you can use [[Precision]], [[Recall]] and [[F measure]] to evaluate model performance.

## Related metrics
- [[Balanced accuracy score]]
- [[Precision]]
- [[Recall]]
- [[F measure]]

## References
- [Sklearn accuracy score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html#sklearn.metrics.accuracy_score)

## Zero Links
- [[Classification Metrics]]