# Week 3


**Table of Contents**
- [Day 1](#day-1)
- [Day 2](#day-2)
- [Day 3](#day-3)

<br>

The goals of this week are to:

- Add more details to our web app
- Learn about neural nets and word representations
- Add neural net and word representation models

<br>

## Day 1

Today we will ...

1. Print the top 15 coefficients for each class at the end of `cli.py::train`function (after you have trained on all data).
2. Modify `routes.py` to also
    - print the confidence of each prediction
    - print the top 3 features responsible for each prediction
3. Do some error analysis:
    - Using your web app, find three examples that are correct and three that are incorrect.
    - For each, look at the top features and the original data to determine what caused the classifier to be correct/incorrect.
    - Brainstorm additional features or changes to the classifier that may help correct these instances. Make these changes and see if it helps. What affect do the changes have on the classification accuracy/F1 in your cross-validation results? Are the three examples from above correctly classified now?


<br>

## Day 2

Today we will ...

1. Review the previous lab. Each team will summarize their results. I will provide comments on your projects thus far.
2. Compare the accuracy of LogisticRegression with two additional classifiers:
  - [MLPClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
  - [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
3. Try different parameters of these two classifiers and record how they affect accuracy:
  - MLP: 
    - hidden_layer_sizes: (10, ), (50, ), (100, ), (200, )
    - alpha: .001, .0001, .00001
  - RandomForest:
    - min_samples_leaf: 1, 3, 5
    - n_estimators: 100, 200, 300 
4. Complete the tensorflow notebook in W3L2.ipynb
<br>

## Day 3

Today we will ...
