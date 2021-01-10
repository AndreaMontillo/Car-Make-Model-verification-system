
the code needed to test the system is inside the file: predict.ipynb

the system is organized as a siamese network with two arms and a final unified part.
Furthermore, we use Yolo in order to detect the car when it is possible. So it is present also
a file with the weights of yolo detector in the file:  YOLO_Weights.h5

Consequently, the system is composed of two model, one in case of detection success 
and the other one in case of a fail of the detection.

these are the two file of weights: Siamese.h5
				   Siamese_withDetection.h5


then the training files that we used are two for the training of the unified part of siamese:
- Siamese.ipynb
- Siamese_withDetection.ipynb

and two for the tha initial part, that is the arms of siamese:
- MobileNet_NoCropResize_DataAug
- MobileNet_CropResize_DataAug


All the training files are not runnable because we extend the training set given to us 
and the training sets used are not in this folder. 
If it is necessary to Run these files, please don't esitate to contact us via email. 

