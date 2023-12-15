#Image feature extraction and classification using SVM model and Resnet50

Step 1:- The dataset has some additional information with images so i loop through those files and collected the images whith respective Healthy, Sick and unknown and there are different types of images was there like Dynamic, Static, Mammography and Thermography images so i organized them with respective there types

step 2:- ResNet50 is used for feature extraction form image 

step 3:- First i picked Dynamic images there was 2201 Healthy images, 596 Sick images and 43 Unknown images 

step 4:- Then i build a model using SVM with 80% as training 20% as testing data

step 5:- used linear kernel to train the data 

step 6:- after Prediction the resulted Accuracy was  98.24%

step 7:- the same steps for Static images and got Accuracy of 80.95%
