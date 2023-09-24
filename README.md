# Urban-Visual-Pollution-Multi-Label-Classification-using-Transfer-Learning
This is a group project for multi class image classification problem on https://www.kaggle.com/datasets/abhranta/urban-visual-pollution-dataset

## Table of Contents
1. [Project Overview](#project-overview)
2. [TechStack](#tech-stack)
3. [Results](#results)

## Project Methodology Overview
The project methodology involved a library and dataset import stage, followed by an initial review of the dataset. Stratified sampling was performed to overcome the limitations of computing devices, maintaining the proportions of the data. One-hot encoding was used to change the labels, while feature extraction was performed to create new features based on the bounding box.

Preprocessing focuses on normalizing and resizing the images, preparing them for analysis. Next, the data was divided into training set (80%) and testing set (20%) for model training and testing.

In modeling, MobileNet and EfficientNet architectures with transfer learning were used. The output layer uses sigmoid activation function and binary_crossentropy loss function for multilabel classification, which is more flexible than softmax.<br>

## Tech Stack and tools

• Python <a href="https://www.python.org/" title="Python"><img src="https://github.com/get-icon/geticon/raw/master/icons/python.svg" alt="Python" width="21px" height="21px"></a>
<br>
• Jupyter Notebook
• Numpy
<br>
• TensorFlow
<br>
• Keras
<br>
• EfficientNet
<br>
• MobileNet

