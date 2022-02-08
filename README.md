# Credit-Card-Fraud-Detection

I have used various Machine Learning algorithms to detect frauds in credit card transaction data. This repository contains codes and reports of the model evaluation results. In summary, the following were the results after training the classification models.

| |Precision | Recall | $F_1$ score | ROC_AUC score |
|---|---|---|---|---|
| SGD Classifier (SGD) | 0.88 | 0.59 | 0.71 | 0.95 |
| Logistic Regression (LR) | 0.89 | 0.65 | 0.75 | 0.97 |
| Random Forests | 0.94 | 0.77 | 0.84 |  |
| Bagging SGD | 0.89 | 0.55 | 0.68 | 0.97 |
| Bagging LR | 0.89 | 0.65 | 0.76 | 0.97 |

We observe that Random Forests has the best recall and $F_1$ score compared to other classifiers.
