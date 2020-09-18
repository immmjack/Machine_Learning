# Machine Learning

This repository contains the application of each algorithms in the field of Machine Learning. I might add something theoretical containing math in the future, but now I need to apply these algorithms. I will start from the **Classification** part.



## Classification

### [Perceptron](https://github.com/immmjack/Machine_Learning/tree/master/Classification/Perceptron/Perceptron.ipynb)

In machine learning, the perceptron is an algorithm for supervised learning of binary classifiers. A binary classifier is a function which can decide whether or not an input, represented by a vector of numbers, belongs to some specific class. (From Wikipedia)

I use the dataset of [**iris**](https://archive.ics.uci.edu/ml/datasets/iris), which can be imported via `from sklearn.datasets import load_iris`. We want to classify the following two cases.

![petal.png](https://github.com/immmjack/Machine_Learning/blob/master/Classification/Perceptron/petal.png?raw=true)

![sepal.png](https://github.com/immmjack/Machine_Learning/blob/master/Classification/Perceptron/sepal.png?raw=true)

I am training for the species **setosa** and **versicolor**.

```
[0] Training_Error: 9 Accuracy: 1.0000 
[1] Training_Error: 0 Accuracy: 1.0000 
[2] Training_Error: 0 Accuracy: 1.0000 
[3] Training_Error: 0 Accuracy: 1.0000 
[4] Training_Error: 0 Accuracy: 1.0000 
[5] Training_Error: 0 Accuracy: 1.0000 
[6] Training_Error: 0 Accuracy: 1.0000 
[7] Training_Error: 0 Accuracy: 1.0000 
[8] Training_Error: 0 Accuracy: 1.0000 
[9] Training_Error: 0 Accuracy: 1.0000
```

This is my training result, but I still haven't found the bug on the accuracy of the 0th line even if I purposedfully calculated training accuracy via `accuracy = 1.0 * correct_count / total_count`.



### Support Vector Machine

