# Transfer-Learning-with-Xception

This is a multi-label image classification project

The provided data contains 20 classes and consists of 31,925 training samples. Some samples have multiple class labels. In these instances if one of label was predicted correctly, then it would be counted as a correct prediciton. 

For modeling purposes we split into 25,000 training samples and 6,925 validation samples.

Both ResNet50 and XceptionNet architecture was tested, the final model was built based on fine tuning the XceptionNet.
