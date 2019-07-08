# Machine Learning Projects

# - Dog Breed Classifier

## Introduction to image recognition

Image recognition is one of the exploding topics in machine learning [1-7]. By building and training state-of-the-art convolutional neural networks, machine learning algorithms can be trained to classify different objects in the images. One of the most famous image recognition projects is ImageNet project, which is an ongoing research effort to provide researchers around the world an easily accessible image database. With the great amount of data in the ImageNet database, researchers participated in the ILSVRC (ImageNet Large Scale Visual Recognition Challenge) had built many useful ML algorithms to classify images into one of 1,000 different categories. One great thing for ILSVRC is that several state-of-the-art algorithms and their pre-trained weights can be easily access through Keras deep learning library and can be further used for transfer learning on new image recognition project.

## Problem Statement: 

Inspired by ImageNet project [8], I work on a CNN project which can be used not only to recognize object in the image but also to learn some interesting features about the recognized image. In this project, I will develop several algorithms that could be used to identify the human, the dog, and also the dog breed from images. The task of assigning breed to dogs from images is considered exceptionally challenging. To see why, consider that even a human would have trouble distinguishing between a Brittany and a Welsh Springer Spaniel and distinguishing between Curly-Coated Retrievers and American Water Spaniels.


<img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/dog_breed_identification_01.png" width="400">   <img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/dog_breed_identification_02.png" width="400">

## Solution Statement: 

Although to identify dog breed from image is challenging, I believe I can build a decent algorithm by learning from ILSVRC and others who had put great efforts on image recognition. At the end of this project, I will build an ML algorithm, which will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.
The images below show example outputs for my ML dog breed classifier. User will supply one image as input, and my classifier will identify its dog breed if human or dog is detected. The output will contain two images: the image on the left will be the original image user supplied with the title showing whether human or dog is detected and the predicted dog breed for this image; the image on the right is an example of dog image having the same breed as that of the original image.

<BR>

Input dog image:
<BR>
<img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/example_doggie_01.png" width="400">

Input human image:
<BR>
<img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/example_human_01.png" width="400">

<br>
<br>
<br>

# - Antimicrobial Peptide (AMP) Classifier

Antimicrobial peptide (AMP) recognition using deep learning

Peptide are short chains of amino acid linked by peptide bonds. Among them, antimicrobial peptides (AMP) are part of the innate immune response found among all classes of life, and have been demonstrated to kill Gram negative and Gram positive bacteria, enveloped viruses, fungi and even transformed or cancerous cells.

One of the research interest in our lab is to understand the mechanism of the peptide and lipid membrane interaction. We are especially interested in AMP peptide and lipid membrane interaction, and have studied many of them to understand the mechanism how AMP peptides kill bacteria by forming different types of pores on bacterias's membrane (Toroidal vs. Barrel Stave Model).

There are two goals we want to achieve using DNN:
(1) To recognize if a given peptide is a AMP peptide or not
(2) To classfy what kind of pores (Toroidal or Barrel Stave) will be formed on bacteria membrane for a given AMP peptide. 

Our first goal is achieved by building a 15 DNN model to reconigze AMP peptides with accuracy >91% on unseen test dataset. The next step of is work is to further classify the pore-forming mechanism (Toroidal vs. Barrel Stave Model) if a given peptide is recoginized as AMP.

<br>
<br>
<br>


# - Digit Reconginer

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
<br>
<br>

# - Sentiment Analysis Web Application

The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review to the deployed model which will predict the sentiment of the entered review. 

IMDB dataset is used to train and validate the XGBoost model. The trained model is then deployed for web application by utilizing AWS Lambda function ana Amazon API Gateway.  

<br>
