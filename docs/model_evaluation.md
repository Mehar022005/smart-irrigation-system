# XGBoost Model Evaluation

## Accuracy
< 0.9960>

## Precision
<High: 1.00>
<Low: 1.00>
<Medium: 0.99>

## Recall
<High: 0.93>
<Low: 1.00>
<Medium: 1.00>

## F1-score
<High: 0.96>
<Low: 1.00>
<Medium: 0.99>

## Observations
- The Low class performed the best, achieving a perfect 1.00 across precision, recall, and f1-score metrics.
- The High class had the lowest performance relative to the others, mainly due to a lower recall of 0.93 and an f1-score of 0.96.
- The High class is slightly more difficult to predict in terms of recall (0.93), meaning the model misses a few true "High" cases, though it is perfectly accurate (precision of 1.00) when it does predict the High class.