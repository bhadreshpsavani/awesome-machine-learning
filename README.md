
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

| Logistic Regression | LinearSVM | SGDClassifier | BernoulliNB | MultinomialNB | GaussianNB |
| --- | --- | --- | --- | --- | --- |
| Supports All types of Classification | Binary | | Binary Features | Integer Features | All type of features |
| Has L1/L2 Regularization | | | consider count of each feature| average | average as well as standard deviation |

C is regularization parameter in Classification, **smalller value of C means simpler model**

## Ensamble Model

* [ensemble-learning-bagging-boosting-stacking](https://www.kaggle.com/code/satishgunjal/ensemble-learning-bagging-boosting-stacking/notebook)
* [/ensemble-methods-machine-learning](https://www.toptal.com/machine-learning/ensemble-methods-machine-learning#:~:text=Ensemble%20methods%20are%20techniques%20that,winning%20solutions%20used%20ensemble%20methods.)
