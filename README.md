# RSNAPneumoniaDetection
Kaggle Challenge to pneumonia in X_RAY images of patients provided by RSNA

In this competition, I was challenged to build an algorithm to detect a visual signal for pneumonia in medical images. Specifically, my algorithm needs to automatically locate lung opacities on chest radiographs.

The training set contained both the train and test set from stage 1. The test set is comprised of new, unseen images.

* X-RAY images are read and processed using pydicom python library. 
* I decided to use Matterpot's mask RCNN neural network model.
* RCNN network was made using resnet as backbone model.
* Prediction is made based on Region of Interests, masks and class id.
* Configuration
  * Epochs =30, 
  * Learning Rate =0.02 
  * Backbone=resnet50 
  * GPU = 1
  * StepsPerEpoch=100
* Accuracy of the model came out to be 86%
  


Note: If you are unable to open jupyter code file, please refresh the jupyter file when asked and try to open it again OR can open the python file instead.
