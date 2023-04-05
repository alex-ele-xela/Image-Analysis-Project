# Comparative Analysis of Image Analysis Algorithms

[![Language](https://img.shields.io/badge/language-jupyter%20notebook-blue)](https://jupyter.org/)
[![Release](https://img.shields.io/badge/release-v1.0-red)](https://github.com/alex-ele-xela/Image-Analysis-Project)

## About

This project aims to compare Machine Learning and Deep Learning algorithms in the case of **Pneumonia Detection** using [Chest X-Ray Images](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) dataset.

## Collaborators

[Alex Prateek Shankar](https://github.com/alex-ele-xela)

[Sneh Shah](https://github.com/sneh2909)

[Souvik Ghosh](https://github.com/souvikghosh2000)

[Zabi Ulla Ismail](https://github.com/zabi-32)

## Introduction

The most common cause of death in children under five is pneumonia, an inflammatory lung disease. According to a UNICEF report, it affected almost 880,000 children in 2020 and was accountable for nearly 16% of all fatalities of children under five. Most of the affected children were under two years old. Early recognition of pediatric pneumonia can aid in accelerating the healing process. In attempting to identify pneumonic lungs from chest X-rays accurately, convolutional neural network models are presented in this research. Medical practitioners can use these models to treat pneumonia in the real world. 
From retrospective cohorts of children patients aged one to five at the Guangzhou Women and Children's Medical Hospital in Guangzhou (Via Kaggle), chest X-ray images (anterior-posterior) were chosen. All chest X-ray imaging was performed as part of the regular clinical treatment provided to patients.

Convolutional neural networks (CNN or ConvNet) are a subclass of neural networks mostly deployed in voice and image recognition applications. With no loss of information, its integrated convolutional layer lowers the high dimensionality of images. CNNs, thus, are very well suited for this use case.

To process an image, feed each pixel as an input to the network. So for an image of size 200 x 200 x 3 (i.e. 200 x 200 pixels with 3 color channels, red, green, blue, etc.), we need to provide 200 * 200 * 3 = 120,000 input neurons. there is. Each matrix is ​​then 200 x 200 pixels or 200 x 200 total entries. This matrix ends up being three times each for red, blue, and green. Then the problem arises in the first hidden layer. This is because each neuron has 120,000 weights from the input layer. 

This means that the number of parameters increases rapidly as we increase the number of neurons in the hidden layer. This challenge is exacerbated when we want to process larger images with more pixels and more color channels. Such networks with a large number of parameters are most likely to lead to overfitting. This means that the model will make good predictions on the training set, but it will not generalize well to new cases that it is not yet aware of. Moreover, due to a large number of parameters, it is very likely that the network will forget the details of individual images. But if you want to classify your photos. Whether there is a dog in it or not, these details such as noses and ears are important for correct results. 

Supervised image classification methods use previously classified reference samples (ground truth) to train a classifier to classify new, unknown data. Supervised classification techniques are, therefore, the process of visually selecting training data samples in images and assigning them to pre-selected categories such as vegetation, roads, water resources, and buildings. This creates a statistical measure that applies to the entire image.  

This research is a comparative study of the accuracy of various Machine Learning and Deep Learning models to validate each model's performance and pick out the best model for Pneumonia Detection.