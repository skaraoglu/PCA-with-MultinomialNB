# PCAwithMultinomialNB

In this project assignment, we focus on principal component analysis (PCA). With employing the MNIST dataset, we train a Multinomial Naive Bayes classifier and test it. Following this experiment, we implemented the PCA on the image dataset with varying parameters and used the outputs to train the same classifier. We compared the accuracy for both experiments to uncover the effects of the PCA.


# Introduction

This project's main point is to introduce the PCA to the classification process. PCA can have some advantages and disadvantages on use, since it's only designed for a single task; feature extraction. On this project, we conduct our experiments on MNIST dataset, a series of images of handwritten digits in black and white format and 28x28 pixel dimensions. Our task is to develop a machine learning system that takes the image of an handwritten digit and predict what number it is. Feature extraction can be highly advantageous in this case. To see the effects of the PCA, we design our experiment on two steps; first, we trained and tested a Multinomial Naive Bayes (Multinomial NB) algorithm on MNIST dataset, further, we implemented PCA on MNIST dataset, then trained and tested the same Multinomial NB classifier with the results of different PCA applications. We presented and compared the accuracy results for different experiments to analyze the effects of the PCA.
