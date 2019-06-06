# Classification-of-Diabetic-Retinopathy-using-Tensorflow

## Packages/libraries required to run the program are:
- Tensorflow
- Anaconda
- Keras
- pip3
- opencv
- pandas
- skitlearn
- matplotlib
- numpy
- Keras VGG16 and Inception Model
- os
- glob

All the above mentioned packages are compatible with python 3.5 interpreter and can be installed and imported using the command line prompt.

## Instructions
 
There are 3 files for the model to execute. The preprocessed images are stored in the test and training data files and the augmentation of the data is also done.

Preprocess_Images.py: This python file performs the preprocessing techique and stores the images respective to the classes in the train and test dat  files.

Data_Augmentation.py: This performs the augmentation process of the compact data.

Train_Test_model.py: This is the main program which uses the contents of the above two files to train the models and eventually test the program. The analyzing part is commented out as it is required for us to analyze. However we included it in the program. It is not necessary to run the analyzing part.

Note: If the train dataset files are not preprocessed, use the Preprocess_Images.py to prepreprocess the images and then run the main program.

To access the training dataset please click the link:
https://drive.google.com/open?id=1sqM-IONor6C3ig9afKYAv6_8u92W3R8m

## Training vs. Validation Accuracy (Inception-V3)
![tra](https://user-images.githubusercontent.com/26629945/59033274-22124d80-888a-11e9-90f8-36f24df6d4db.JPG)

## Learning Curve Loss (Inception-V3)
![lc](https://user-images.githubusercontent.com/26629945/59033403-75849b80-888a-11e9-9e6e-3de75480e7e1.JPG)

## Training vs. Validation Accuracy (VGG-16)
![vgg](https://user-images.githubusercontent.com/26629945/59033549-c3010880-888a-11e9-92b2-af9a1eeb50e0.JPG)

## Learning Curve Loss (VGG-16)
![vgglc](https://user-images.githubusercontent.com/26629945/59033607-ddd37d00-888a-11e9-908a-88db1690be87.JPG)

## Confusion Matrix
![cf](https://user-images.githubusercontent.com/26629945/59032971-58030200-8889-11e9-910d-c68a003ae7c7.JPG)

