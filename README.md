# text categorization

This code use cnn to achieve Chinese text categorization

Operating environment: Ubuntu16.04 Python3.6.3

train execute to get model:

```python
python3 tc.py train
```

test execute:

```python 
python3 tc.py test
```
The result of test:

```bash
Testing...
Test Loss:   0.37, Test Acc:  93.96%
Precision, Recall and F1-Score...
precision    recall  f1-score   support

    0       0.95      0.98      0.96      7783
    1       0.90      0.81      0.86      2217

avg / total       0.94      0.94      0.94     10000

Confusion Matrix...
        [[7591  192]
        [ 412 1805]]
Time usage: 0:00:04Testing...
Test Loss:   0.37, Test Acc:  93.96%
```
