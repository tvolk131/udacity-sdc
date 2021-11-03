# Computer Vision Notes

## Machine Learning Metrics

### Terminology

#### True Positive (TP)
When a model correctly predicts the positive outcome for a given input (i.e. a model that predicts whether or not an image contains a burger returns true for an image that contains a burger)
#### False Positive (FP)
When a model correctly predicts the negative outcome for a given input (i.e. a model that predicts whether or not an image contains a burger returns true for an image that does not contain a burger)
#### True Negative (TN)
When a model correctly predicts the positive outcome for a given input (i.e. a model that predicts whether or not an image contains a burger returns false for an image that does not contain a burger)
#### False Negative (FN)
When a model correctly predicts the negative outcome for a given input (i.e. a model that predicts whether or not an image contains a burger returns false for an image that contains a burger)

### Equations

#### Precision = TP/(TP + FP)
Of the elements classified as a particular class, how many did we get right?
#### Recall = TP/(TP + FN)
Of the elements labeled as a particular class, how many did we get right?
#### Accuracy = (TP + TN)/(TP + FN + FP + TN)
The number of correctly classified images over the total number of images.