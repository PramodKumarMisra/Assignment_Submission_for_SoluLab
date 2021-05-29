# Assignment_Submission_for_SoluLab      <img src='https://cdn3.iconfinder.com/data/icons/sociocons/256/github-sociocon.png' alt='github' height='40'>
![Generic badge](https://img.shields.io/badge/Machine-Learning:-green.svg)                              ![Generic badge](https://img.shields.io/badge/Python-V3:-blue.svg)        ![Generic badge](https://img.shields.io/badge/TensorFlow-Keras:-orange.svg)               ![Generic badge](https://img.shields.io/badge/SciPy-sklearn:-green.svg)                  ![Generic badge](https://img.shields.io/badge/C:Newral-Network:-white.svg)   
This repo, only for Assignment Submission  for SoluLab 


![Generic badge](https://img.shields.io/badge/Problem_Statement-:-blue.svg)  
To use the given coin dataset to classify the coins between 5 categories. 

The labels of the coins are given in the file names, example if the name of the file is 5_1477145580.jpg then the coin has value 5 which is before ‘_’ in the file name


![Generic badge](https://img.shields.io/badge/Limitations-:-red.svg) 

●	Use any machine learning algorithm to create your own classification model.

●	The model should give 5 outputs (5, 10, 25, 50, 100) that will be the value of that coin.

●	Split the dataset into training and test sets and provide the accuracy of the test set.


![Generic badge](https://img.shields.io/badge/Datasets-Link-green.svg) 

Click Here : https://www.kaggle.com/lgmoneda/br-coins/download



![Generic badge](https://img.shields.io/badge/Proposed-Solution:-orange.svg) 

I'm using image recognition techniques to separate the coins, classify them on their own.
I am doing this with datasets since it makes the algorithm more flexible, mostly it seems that the segmentation part is fine with minor error rates and that most of the issues with the multi-coin task can be explained as statistical error if we consider 97% accuracy for classification (just a regular classifier) and an average of 7-8 coins in the image

I have been trying to solved this problem using  **Machine Learning**/**Deel Learning** algorthms known as **Convolutional Newral Network(CNN)** for better accuracy. I wants to use data augmentation technique but we have sufficient data sets which's give use 80%+ accuracy that why i'm skip it.
