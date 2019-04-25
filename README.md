# Outlier-Detection

This Outlier/Anomaly detection started from this [question](https://machinelearningphd.com/outlier-detection-svm/).
It explores the features extracted and then use Sklearn's [One Class Support Vector Machine](https://scikit-learn.org/stable/modules/generated/sklearn.svm.OneClassSVM.html) (OC-SVM) to gain decent results.

1. Load the dataset onto the RAM for faster execution
2. To extract features, we use the pre-trained Resnet50 weights.
3. Normalize the input using Standard scalar
4. Reduce the number of channels using PCA
5. Use GridSearch in order to find the parameters for One Class SVM.
6. Plot the Confusion Matrix to know the accuracy.
