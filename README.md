# Scene-Classification-using-Spatial-Pyramid-Matching

## Project Summary

This project demonstrates the application of the Statistical Pyramid Matching (SPM) on the bag-of-words (BoW) approach. BoW approach is used for object recognition and scene classification. This project contains training and testing cases of images. 60 features has been generated for each image. From those 60 features, visual words has been created using K-Means clustering, which has been used as dictionary. Dictionary is then used for generating visual words vector for every images. Section 2 helps us to implement SPM approach on the on the histograms generated from the visual words vector of different images. We trained our algorithm based upon the 3-layered histograms matching. Finally we checked for the accuracy of the trained algorithm in classifying 160 test images.

## Documentation
***
Project report can be found at [report](https://github.com/jayantsolanki/scene-classification-using-SPD/blob/master/report/report.pdf) link

## Folder Tree
***
* [**docs**](https://github.com/jayantsolanki/scene-classification-using-SPD/tree/master/docs) contains original problem statement
* [**report**](https://github.com/jayantsolanki/scene-classification-using-SPD/tree/master/report) contains report having implementation details
* [**src**](https://github.com/jayantsolanki/scene-classification-using-SPD/tree/master/src) contains implementation code in Matlab
