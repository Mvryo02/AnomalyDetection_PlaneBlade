# AnomalyDetection_PlaneBlade

This prject aims to detect anomalies in a dataset of engine plane blade. For this problem two possible solution have been explored:
- Autoencoder;
- Autoencoder with resnet feature extraction.
  
We also  developed a classifier, in order to classify the anomalies after detecting one.

In this repository it is possible to find: 
- train and test sets for detectors;
- train and test sets for classifiers;
- project presentation;
- code developed. 

In the code are present:
- the operation for pre-process the data (sharpen filter, resize, ...)
- the definition of autoencoders
- training and testing for the autoencoder;
- code to extract features from a ResNet50;
- definition, training and testing for solution with feature extraction through the ResNet50;
- definition, training and testing code for classifiers.
