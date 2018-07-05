# Detection-and-Tracking-of-Cars-Vehicles-using-Computer-Vision

## Steps involved:

1. Data evaluation

Analysis of data.
Classification of car and not-car images.
HOG feature extraction.
Visualization of HOG features of images.  

2. HOG classifiers and SVC training

Extracting features from list of images.
Train a linear support vector machine (SVM) classifier.

3. Car/Vehicle detection pipeline

Predicting over feature extracted images and to draw bounding boxes
Sliding window technique is applied by varying parameters and detection is by trained classifiers
Heat map is genearted based on rectangular locations and boundng boxes apples on labels
Run a video through the pipeline

## Datasets used:

[GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html)

