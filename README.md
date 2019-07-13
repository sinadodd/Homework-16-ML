# Summary
Random Forest is better than SVM, even without GridSearchCV.
***

## **SVM**

|                | Before CV   | After CV  |
| -------------- |:-----------:| :--------:|
| Training Score | 0.85026     | 0.88777   |
| Testing Score  | 0.83898     | 0.88106   |

---

|                | precision| recall   | f1-score  | support |
| -------------- |---------:| --------:| ---------:| -------:|
| CANDIDATE      | 0.85     | 0.65     | 0.73      | 523     |
| CONFIRMED      | 0.75     | 0.87     | 0.81      | 594     |
| FALSE POS      | 0.98     | 1.00     | 0.99      | 1069    |
| micro avg      | 0.88     | 0.88     | 0.88      | 2186    |
| macro avg      | 0.86     | 0.84     | 0.84      | 2186    |
| weighted avg   | 0.88     | 0.88     | 0.88      | 2186    |

***

## **Random Forest**

|                | Before CV   | After CV  |
| -------------- |------------:| ---------:|
| Training Score | 0.99497     | 1.0       |
| Testing Score  | 0.87740     | 0.89616   |

---

|                | precision| recall   | f1-score  | support |
| -------------- |---------:| --------:| ---------:| -------:|
| CANDIDATE      | 0.84     | 0.73     | 0.78      | 523     |
| CONFIRMED      | 0.81     | 0.86     | 0.83      | 594     |
| FALSE POS      | 0.97     | 1.00     | 0.98      | 1069    |
| micro avg      | 0.90     | 0.90     | 0.90      | 2186    |
| macro avg      | 0.87     | 0.86     | 0.87      | 2186    |
| weighted avg   | 0.89     | 0.90     | 0.89      | 2186    |