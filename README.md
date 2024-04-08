# Traffic Sign Detection

## Overview

This project is about detecting traffic sign based on [this dataset](https://drive.google.com/file/d/1YJiHQeLotsaXAXCtLLKBHPaawqKiSC5b/view). The dataset contains 877 images with 4 classes sequentially 'traffic light', 'stop', 'speedlimit' and 'crosswalk'. 

There are two files, annotations file contains information and label of each images, and images file contains images storing in png form. 

Project used SVM to predict results for each labels, and using techniques like pyramiding images, sliding windows and non-maximum suppression to localize the objects.  

## Outline 
1. Loading data
2. Preparing data
3. Training model
4. Localizing objects
5. Showing results



