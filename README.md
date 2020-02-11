# Supervised Learning
- Is one of the most commonly used types of machine Learning.
- Is used when we want to to predict a certain outcome from a given input, and we have examples ofinput/output pairs.
- Using the input/output pairs we can build a ML model (training set).
- The goal is to make accurate predictions for new (never-before-seen) data.
- We can say that the a supervised learning model is able to *generalize* from the training set to the test set if it's able to make accurate predictions on unseen data.
- We always want to find the simplest model.
- *Overfitting*: build a model that is too complex for the amount of data we have.
- *Underfitting*: Choosing too simple a model

The two major types of supervised ML problems are *classification* and *regresion*.

### Classification tasks
- The goal is to predict a *class label* (a choice from predefined list of posibilities)
- Often separated into *binary classification* (distinguishing between exactly two classes) and *multiclass classification* (classification between more than two classes).

### Regression tasks
- The goal is to predict a continous number (floating-point number)

### Model Complexity - Dataset Size Relation
- The larger variety of data points the dataset contains, the more complex a model you can use.
- However, simply duplicating the same datapoints or collecting very similar data will not help.
