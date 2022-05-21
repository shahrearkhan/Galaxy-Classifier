# Galaxy-Classifier
# Shahrear Khan Faisal & Jaime Alvarez Perez

# Introduction

In this prooject we have created a classification method using Convolutional Neural Network (CNN) that will be able to classify 5 classes of galaxies according to their morphologies. We developed our own CNN model from scratch and used the galaxy10 dataset to train our model. The oroginal dataset contains 10 class labels. However, due to imbalance in the amount of data in different labels, we discarded 5 classes with insufficient number of data and used the other 5 to train the model. We were able to achieve 89% validation accuracy.

# CNN Architecture

![archi](https://user-images.githubusercontent.com/77114327/169652493-32835a7f-d667-4a96-b32c-d786d939c91b.png)

# Results
We achieved 89% validation accuracy with 400 epochs.

![unnamed](https://user-images.githubusercontent.com/77114327/169652650-8347b3d1-26e9-4105-a6ae-30312b384173.png)

# References
1. Galaxy10 Dataset - https://astronn.readthedocs.io/en/latest/galaxy10.html
2. Kim, E. J., & Brunner, R. J. (2016). Star–galaxy classification using deep convolutional Neural Networks. Monthly Notices of the Royal Astronomical Society, 464(4), 4463–4475. https://doi.org/10.1093/mnras/stw2672 


