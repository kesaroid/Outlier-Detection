# Anomaly-Detection

This Outlier detection is an implementation of this [Hackernoon article](https://hackernoon.com/one-class-classification-for-images-with-deep-features-be890c43455d).
It explores the feature extraction part and then use Sklearn's One Class Support Vector Machine (OC-SVM) to gain decent results.

1. Load the dataset onto the RAM for faster execution
2. To extract features, we use the pre-trained Resnet50 weights.
3. Normalize the input using Standard scalar
4. Reduce the number of channels using PCA
5. Use GridSearch in order to find the parameters for One Class SVM.
6. Plot the Confusion Matrix to know the accuracy.
