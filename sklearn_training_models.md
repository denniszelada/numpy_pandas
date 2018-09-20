# Training Models in Scikit learn

## Logistic Regression
```python
from sklearn.linear_model import LogisticRegression
classifier = LogisticRegression()
```

## Neural Networks
> This is only available on version 0.18 or higher of scikit-learn
```python
from sklearn.neural_network import MLPClassifier
classifier = MLPClassifier()
```

## Decision Trees
```python
from sklearn.tree import DecisionTreeClassifier
classifier = DecisionTreeClassifier()
```

## Support Vector Machines
> We can pass optional params:
 * kernel (string): 'linear', 'poly', 'rbf'.
  * degree (integer): This is the degree of the polynomial kernel, if that's the
    kernel you picked (goes with poly kernel).
  * gamma (float): The gamma parameter (goes with rbf kernel).
  * C (float): The C parameter.

```python
from sklearn.svm import SVC
classifier = SVC()
```

## Logistic Regression
```python
from sklearn.linear_model import LogisticRegression
classifier = LogisticRegression()
classifier.fit(X,y)
```
