# Digit Reconginer


How well can a machine learning algorithm classify hand-written digits?

In this Kaggle competition Digit Recongnizer, our goal is to build a best digit recongnizer that can recongnize hand-written digits with the accuracy close to or even better than whtat humans can do.

The CNNs in this kernel follow LeNet5's design with the few improvements:

- ReLU activation replaces sigmoid.
- Batch normalization is added
- Dropout is added
- More feature channels are added
- An ensemble of 5 CNNs with bagging is used

In this kernal, we have built a ensemble of CNNs that can achieve more than 99.7% of classification accuracy on the unseen test data. Based on the LeNet-5 architecture, few advanced techniques are used including data augmentation, ReLU activation, ensembling, bagging, decaying learning rates, dropout, batch normalization, and adam optimization.

<br>
