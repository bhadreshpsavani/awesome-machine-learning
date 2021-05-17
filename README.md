
## Regularization:

| L2 | L1 |
| --- | --- |
| penalizes higher value of weights and tries to center it towards zero | Reduce Features |
| | Makes model more interpretable because of less features |

## Regression Algorithms:

| Linear | Ridge | Lasso | SGDRegressor |
| --- | --- | --- | --- | 
| Without Regularization | L2 | L1 | |

Alpha is regularization parameter in Regression, **Large value of alpha means simpler model**

## Classification:

* Precision(P): True Positive / Predicted Positive 
* Recall(R) / Sensitivity: True Positive / Actual Positive
* F1 Score : 1/F1 = 1/2(1/P + 1/R) , If P or R is having low value it will make sure overall score is lower

| Logistic Regression | LinearSVM | SGDClassifier |
| --- | --- | --- |
| Supports All types of Classification | Binary | |
| Has L1/L2 Regularization | | |

C is regularization parameter in Classification, **smalller value of C means simpler model**
