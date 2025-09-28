# Financial Fraud Detection - Synthetic Mini Project

Generated on 2025-09-16 11:08:32 UTC


## Dataset

- Number of rows: 20000

- Fraud ratio: 0.0144


## Models & Evaluation

### LogisticRegression

- ROC AUC: 0.5504

- Confusion matrix (test):
```
[[4928    0]
 [  72    0]]
```

- Fraud class (1) — precision: 0.0000, recall: 0.0000, f1: 0.0000


### RandomForest

- ROC AUC: 0.4509

- Confusion matrix (test):
```
[[4928    0]
 [  72    0]]
```

- Fraud class (1) — precision: 0.0000, recall: 0.0000, f1: 0.0000


### GradientBoosting

- ROC AUC: 0.4986

- Confusion matrix (test):
```
[[4904   24]
 [  70    2]]
```

- Fraud class (1) — precision: 0.0769, recall: 0.0278, f1: 0.0408


### IsolationForest (unsupervised)

- ROC AUC (against true labels): 0.4978129509379509

