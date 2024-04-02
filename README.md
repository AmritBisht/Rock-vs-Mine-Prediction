# Rock-vs-Mine-Prediction
## About
Sonar technology has revolutionized underwater exploration by enabling the detection of rocks and minerals that would be nearly impossible to find with traditional methods. It works by analyzing specific parameters of sound waves that bounce back from objects, allowing us to identify and locate submerged targets and obstacles like rocks or mines.

In the realm of cutting-edge technology, machine learning has emerged as a dominant force, impacting everything from finance to consumer goods and product-based industries. Its advancements in predictive analytics hold immense potential. One such algorithm used for this prediction is logistic regression, which is implemented in google colab.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ONVp8a-i-I0E6ZjoOXX5aIKfsWF4LECf?usp=sharing)

## DataSet
The dataset has
been collected from UCI Repository. It has come
across 61 features which define and differentiate
Rocks and Mines and comprises of 209 samples. 
This data is used for training and testing purpose. The Last column in this dataset 
indicates that, whether it's a mine or a rock, which is useful in prediction.
The dataset is included in this repository.

## Model
The model used here is  **Logistic Regression**. Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. Logistic Regression uses a sigmoid or logit function which will squash the best fit straight line that will map any values including the exceeding values from 0 to 1 range. So it forms an “S” shaped curve. Sigmoid func. removes the effect of outlier and makes the output between 0 to 1.
As it a binary classification model it is perfect to predict if an object is mine or rock based on the sonar data.

## Description
![screenshot](https://github.com/AmritBisht/Rock-vs-Mine-Prediction/blob/main/workflow.png)
Sonar data in a csv file is taken for training and testing purpose. Data preprocessing is done on the available sonar data which is suitable for training the model. After Data preprocessing, a Logistic regression model is built. The dataset is split into testing and training sets. The training data is used to train the model then the new data/ testing data is given to the trained logistic regression model for prediction.  

## Acknowledgements

  - [Prediction of Underwater Surface Target through SONAR](https://www.jetir.org/papers/JETIR1907H24.pdf)
 
