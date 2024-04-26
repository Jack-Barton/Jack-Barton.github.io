# ROC Curves
Today I learned about ROC curves (receiver operating characteristic curves) for classiffication models.
## Why use ROC curves

![](/images/Roc_curve.png "ROC Curve")

ROC curves show the quality of your classification model where, as the curve aproaches the top left corner it can be seen as a better 
model as seen in the image above.

## What do the axes mean
On the y-axis is the "True Positivive Rate" which represents the rate at wich the model can correctly identify a match when 
match threshold is varied from 0-1
On the x-axis is the "False Positive Rate" which represents the rate at which the model incorectly identifies a match when
match threshold is varied from 0-1

## Ideal ROC curve
The ideal ROC curve has a true positive rate of 1 and false positive rate of 0 which represents a model that is 100% accurate 
with 0% false positives 
