# Object Recognition
Source: DPhi challenger 31
https://dphi.tech/practice/challenge/31

## Objective: classify images into 10 classes of objects: 
* Ship
* Aeroplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Truck

Training data is the cifar10 library: size 50,000. Image size 32x32.

## Simple EDA

## Data preprocess
* normalization

## build models 

### 3.1 simple MLP
Did not yield satisfying results  

<img src = "https://github.com/sindhri/object_classification/blob/master/doc/img/model1.png" width = "200">

### 3.2 deeper MLP
Did not yield satisfying results
<img src = "https://github.com/sindhri/object_classification/blob/master/doc/img/model2.png" width = "200">

### 3.3, 3.4 deeper MLP with more parameters
Did not yield satisfying results
<img src = "https://github.com/sindhri/object_classification/blob/master/doc/img/model3.png" width = "200">


### 3.5, simple CNN
test accuracy is 69%, consistent with validation accuracy
<img src = "https://github.com/sindhri/object_classification/blob/master/doc/img/model5.png" width = "200">


### 3.6, larger CNN
after 50 epochs (18 hours), the validation accuracy is still only 78%, test accuracy was the same
<img src = "https://github.com/sindhri/object_classification/blob/master/doc/img/model6.png" width = "200">


