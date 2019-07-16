This repository contains all major files used to create my first Keras based Image classifier to distinguish between Cats and Dogs.
I have taken around 25000 images of equally distributed collection of images belonging to both cats and dogs. These were further split in
the ratio of 80:20 for training and test subsets. The following depicts the number of images used per class for various ML pipelines.

                        Cat        Dog

Train                 10000       10000    
Test                   2500        2500
Validation             2500        2500

Problem statement :
In this Section we are implementing Convolution Neural Network(CNN) Classifier for Classifying dog and cat images. The Total number of images available for training is 25,000 and final testing is done on seperate 10,000 images.

Note:This problem statement and dataset is taken from this Kaggle competition.
Dependencies
Jupyter notebook
Tensorflow 1.10
Python 3.6
Matplotlib
Seaborn
Scikit-Learn
Pandas
Numpy
Install dependencies using conda

Test Train Split
Image training set contain 12500 images for each category. I split those into 80% train and 20% means test Split each class images into 10,000 for train and 2,500 for test.




Conclusion
The Architecture and parameter used in this network are capable of producing accuracy of 97.56% on Validation Data which is pretty good. It is possible to Achieve more accuracy on this dataset using deeper network and fine tuning of network parameters for training. You can download this trained model from resource directory and Play with it.
