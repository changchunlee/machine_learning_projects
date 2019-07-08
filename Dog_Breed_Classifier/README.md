# Dog Breed Classifier

## Introduction to image recognition

Image recognition is one of the exploding topics in machine learning [1-7]. By building and training state-of-the-art convolutional neural networks, machine learning algorithms can be trained to classify different objects in the images. One of the most famous image recognition projects is ImageNet project, which is an ongoing research effort to provide researchers around the world an easily accessible image database. With the great amount of data in the ImageNet database, researchers participated in the ILSVRC (ImageNet Large Scale Visual Recognition Challenge) had built many useful ML algorithms to classify images into one of 1,000 different categories. One great thing for ILSVRC is that several state-of-the-art algorithms and their pre-trained weights can be easily access through Keras deep learning library and can be further used for transfer learning on new image recognition project.

## Problem Statement: A ML algorithm to identify dog breed

Inspired by ImageNet project [8], I work on a CNN project which can be used not only to recognize object in the image but also to learn some interesting features about the recognized image. In this project, I will develop several algorithms that could be used to identify the human, the dog, and also the dog breed from images. The task of assigning breed to dogs from images is considered exceptionally challenging. To see why, consider that even a human would have trouble distinguishing between a Brittany and a Welsh Springer Spaniel and distinguishing between Curly-Coated Retrievers and American Water Spaniels.


<img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/dog_breed_identification_01.png" width="400">   <img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/dog_breed_identification_02.png" width="400">

Although to identify dog breed from image is challenging, I believe I can build a decent algorithm by learning from ILSVRC and others who had put great efforts on image recognition. At the end of this project, I will build an ML algorithm, which will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.
The images below show example outputs for my ML dog breed classifier. User will supply one image as input, and my classifier will identify its dog breed if human or dog is detected. The output will contain two images: the image on the left will be the original image user supplied with the title showing whether human or dog is detected and the predicted dog breed for this image; the image on the right is an example of dog image having the same breed as that of the original image.

<BR>

Input dog image:
<BR>
<img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/example_doggie_01.png" width="400">

Input human image:
<BR>
<img src="https://raw.githubusercontent.com/changchunlee/machine_learning_projects/master/Dog_Breed_Classifier/images/example_human_01.png" width="400">

