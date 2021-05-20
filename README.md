# logistic-regression-income-classification
Income class classification using logistic regression.

Income classification dataset from kaggle.com
Link to dataset: https://www.kaggle.com/lodetomasi1995/income-classification

Accuracy: 0.80

F1-score:

||f1-score|
|--|--|
|<=50k|0.88|
|>50k|0.41|

Lower f1-score for >50k is because low percentage of data on it, only 0.24 from the whole dataset.

Confusion Matrix:

| |Predicted: NO| Predicted: YES|
|-|-------------|---------------|
| Actual: NO |7202|234|
| Actual: YES |1681|652|