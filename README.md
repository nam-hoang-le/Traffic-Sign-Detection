# Traffic Sign Detection

## Overview

This project focuses on detecting traffic signs using a dataset consisting of 877 images with 4 classes: 'traffic light', 'stop', 'speed limit', and 'crosswalk'. The dataset is comprised of two files: an annotations file containing information and labels for each image, and an images file containing the images stored in PNG format.

The project employs Support Vector Machine (SVM) for predicting results for each label. Techniques such as image pyramiding, sliding windows, and non-maximum suppression are utilized to localize the objects accurately.

# Outline
1. Loading Data: The dataset is loaded, including both the images and their corresponding annotations.

2. Preparing Data: Data preprocessing steps are performed, including resizing images and extracting features.

3. Training Model: An SVM model is trained using the preprocessed data to predict traffic sign labels.

4. Localizing Objects: Techniques like image pyramiding and sliding windows are applied to localize the objects within the images.

5. Showing Results: The results of the traffic sign detection process are visualized, showcasing the effectiveness of the model in accurately identifying and localizing traffic signs.

6. Feel free to explore the repository to understand the implementation details and see the results of traffic sign detection using SVM and various localization techniques.
