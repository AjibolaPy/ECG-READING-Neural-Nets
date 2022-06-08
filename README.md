# ECG-READING-Neural-Nets

An electrocardiogram (ECG) is a simple test that can be used to check your heart's rhythm and electrical activity.
An ECG is often used alongside other tests to help diagnose and monitor conditions affecting the heart
The role of automatic electrocardiogram (ECG) analysis in clinical practice is limited by the accuracy of existing models.
Neural Networks are models composed of stacked layers that learn tasks by examples. The advent of Deep learning Neural Network has achieved striking success in varieties of tasks and there are great expectations on its improvement in clinical practice. 
I present a Deep Neural Network model trained on a dataset with  hundred thousand labeled exams. 
This dataset is composed of two collections of heartbeat signals derived from two famous datasets in heartbeat classification, the MIT-BIH Arrhythmia Dataset and The PTB Diagnostic ECG Database. The number of samples in both collections is large enough for training a deep neural network.

This model acheived 97% accuracy on the training data and 98% on the test data.
It Comprises of two 1D Convolutional Neural Networks stacked together and two GRU layers.
the 1D Conv Net downsamples the large dataset picking only important features.
The model is able to classify 5 types of heart rhythms correctly.

