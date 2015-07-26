OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks

2014 ICLR, Pierre Sermanet, David Eigen, Xiang Zhang, Michael Mathieu, Rob Fergus, Yann LeCun

### Algorithm

Integrated framework for classification,localization and detection

**the fully-connected layers can also be seen as 1x1 convolutions in a spatial setting**
--> don't care input size

* Classification
  multi-scale

* Localization
  replace the classifier layers by a regression network, output with coordinates of bounding box
  regressor layer is class-specific

* Detection
   main difference: predict a background class when no object is present.