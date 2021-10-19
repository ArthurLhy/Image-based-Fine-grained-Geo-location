# Image-based Fine-grained Geo-location withLearned Features and Matching





## COMP90086 COMPUTER VISION 2021 S2

### TEAM NAME: GROUP 7

#### TEAM MEMBER:

*TIANHAO SHI 629394*
*HUANGYU LIU 1046223*



## Libaray requirement

*(All codes are implemented on Jupyter Notebook and Google Colab)*

 jupyter notebook

- Tensorflow 2.5.0
- Python 3.7.0
- Numpy 1.21.2
- Opencv 4.5.1
- Pandas 1.3.2
- matplotlib 3.3.4
- sklearn



## LOADING data

Unzip the data directly under the same directory of the code file.

**RUN -> read files**



## SIFT

Feature extraction and pre-train FLANN matcher
**RUN -> SIFT train feature extraction**

Predict query image location
**RUN -> FLANN matching**

Test and check query image
SELECT test_idx from 0 to 1199 
**RUN -> experiments on ORB results (Test1 and Test3)**

*(NOT IN USED CELL for camera pose estimation*
*test step 5 - mutliview depth*
*display multiview result*
*test 4 epipolar geometry for camera pose estimation)*



## ORB

Feature extraction and pre-train FLANN matcher
**RUN -> ORB train feature extraction**

Predict query image location
**RUN ->Matching**

Test and check query image
SELECT test_idx from 0 to 1199 
**RUN -> experiments on ORB results (Test1 -> Test2 -> Test3)**





## Deep-learning

Preparing the library and feature extraction model
**RUN -> preparing feature extraction model**

Read the labels 
**RUN -> read the labels **

preparing training model and training the model
**Run -> 4c and 4d**

Predict the result of location. of the test images with above model
**Run -> predict the location with the model and save the result**



