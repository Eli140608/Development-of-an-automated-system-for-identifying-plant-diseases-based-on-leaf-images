# Development-of-an-automated-system-for-identifying-plant-diseases-based-on-leaf-images

The goal of this project is to implement a plant disease recognition system based on the approach proposed in the article "Automatic recognition of plant leaves diseases based on serial combination of two SVM classifiers" and Chapter 1: "Automatic recognition system for damage and symptoms on plants". The proposed method involves several steps, including preprocessing, segmentation, and feature extraction, using OpenCV.

In the preprocessing step, the input image is first resized and converted to grayscale. Then, various filters are applied to remove noise and enhance the contrast of the image. Next, the image is segmented into regions of interest (ROIs) using a thresholding technique.

In the segmentation step, the ROIs are further processed to extract meaningful features such as color, shape, and texture. This is achieved by using various image processing techniques such as edge detection, morphological operations, and feature extraction algorithms.

In the feature extraction step, the extracted features are transformed into a fixed-size feature vector that can be used as input to a machine learning algorithm. Support Vector Machines (SVMs) are used in this project for classification, as proposed in the referenced article.

Overall, this project aims to provide a robust and efficient solution for plant disease recognition using OpenCV and SVMs.
