# RSNAPneumoniaDetection
Kaggle Challenge to pneumonia in X_RAY images of patients provided by RSNA

In this competition, I was challenged to build an algorithm to detect a visual signal for pneumonia in medical images. Specifically, my algorithm needs to automatically locate lung opacities on chest radiographs.
* Initially the images were processed using various techniques like run length encoding, image augemtation, creating masks of ships etc. 
* We decided to use Image segmentation in our CNN.
* Slight variation of U-Net model was used (https://arxiv.org/pdf/1505.04597.pdf).
* The result was calculate as Intersection over Union(IoU).
* The model uses "Adam optimizer" and metrics is "Binary accuracy".


Note: If you are unable to open jupyter code file, please refresh the jupyter file when asked and try to open it again OR can open the python file instead.
