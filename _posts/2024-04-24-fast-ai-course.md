# The Multiclass Classifier (CIFAR10 Classes)

## Is it a airplane, automobile, bird, cat, deer, dog, frog, horse, ship or truck?
<img src="../images/cifar10.png"  width="30%" height="30%">

The basic steps taken are as follows:
1. Use DuckDuckGo to search for images of airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships and trucks
1. Fine-tune a pretrained neural network to recognise these groups (resnet18)
1. Try running this model on a picture of an airplane and see if it works.

## Step 1) Data collection
In the first step you can scrape as many images as you would like for each class from the DuckDuckGo search engine to produce a data set for training the nural net. this can be done by defining how maney images you want along with a for loop pulling images with different search prompts of for each class item you want to identify.

A multiclass image classifier is a nural network (NN) that can be passed the pixel values of an image and output a correlation percentage for each class being analysed. 

<img src="../images/nn.png"  width="30%" height="30%">

