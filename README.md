# Machine Learning Projects

## 1. Antimicrobial Peptide (AMP) Classifier

Antimicrobial peptide (AMP) recognition using deep learning

Peptide are short chains of amino acid linked by peptide bonds. Among them, antimicrobial peptides (AMP) are part of the innate immune response found among all classes of life, and have been demonstrated to kill Gram negative and Gram positive bacteria, enveloped viruses, fungi and even transformed or cancerous cells.

One of the research interest in our lab is to understand the mechanism of the peptide and lipid membrane interaction. We are especially interested in AMP peptide and lipid membrane interaction, and have studied many of them to understand the mechanism how AMP peptides kill bacteria by forming different types of pores on bacterias's membrane (Toroidal vs. Barrel Stave Model).

There are two goals we want to achieve using DNN:
(1) To recognize if a given peptide is a AMP peptide or not
(2) To classfy what kind of pores (Toroidal or Barrel Stave) will be formed on bacteria membrane for a given AMP peptide. 

Our first goal is achieved by building a 15 DNN model to reconigze AMP peptides with accuracy >91% on unseen test dataset. The next step of is work is to further classify the pore-forming mechanism (Toroidal vs. Barrel Stave Model) if a given peptide is recoginized as AMP.

<br>

## 2. Digit Reconginer


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

## 3. Sentiment Analysis Web Application

The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review to the deployed model which will predict the sentiment of the entered review. 

IMDB dataset is used to train and validate the XGBoost model. The trained model is then deployed for web application by utilizing AWS Lambda function ana Amazon API Gateway.  

<br>
