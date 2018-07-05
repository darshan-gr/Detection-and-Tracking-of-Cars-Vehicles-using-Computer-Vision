# Detection-and-Tracking-of-Cars-Vehicles-using-Computer-Vision

## Steps involved:

1. _**Data evaluation**_

    * Analysis of data
 
    * Classification of car and not-car images
 
    * HOG feature extraction
 
    * Visualization of HOG features of images  

2. _**HOG classifiers and SVC training**_

     * Extracting features from list of images
  
     * Train a linear support vector machine (SVM) classifier

3. _**Car/Vehicle detection pipeline**_

     * Predicting over feature extracted images and to draw bounding boxes
  
     * Sliding window technique is applied by varying parameters and detection is by trained classifiers
  
     * Heat map is genearted based on rectangular locations and boundng boxes apples on labels
  
     * Run a video through the pipeline

 _**Datasets used**_:

[GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html)

[KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/)

[caltech database](http://www.vision.caltech.edu/html-files/archive.html)

[TU Graz database](http://www-old.emt.tugraz.at/~pinz/data/GRAZ_02/)

[Udacity labelled sets](https://github.com/udacity/self-driving-car/tree/master/annotations)

