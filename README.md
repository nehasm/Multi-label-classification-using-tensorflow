# Multi-label-classification-using-tensorflow


This is the multi label classification model in which the data contains 6 classes.The dataset for the same is available [here](https://www.kaggle.com/asdasdasasdas/garbage-classification).The dataset have 2527 images of 6 classes namely cardbaord,paper,plastic,trash,glass and metal.The model can used in a garbage classification project.The model is trained on GPU using google colabalatory.The model acheived 83% accuracy on training data and 73% accuracy on test data.

 ###  `Model Details`
 
* The data is generated through ImageDataGenarator with proper augmentation.
* The sequential model is written using tensorflow.keras.The model flow the architecture of VGG16 for multi level classification.
* After model structure,the model is compile using adam optimizer with categorical_crossentropy loss.
* Weights file is created to save the best weights in it (you can download it from [here](https://drive.google.com/file/d/1zU6KjFmHE0bko9wZQcY41pXUEQ0ftBVI/view?usp=sharing)).
* Model is trained by defining number of epoch,step size and batch size.
* Loss and accuracy of model is monitor for further steps.
* Model is evaluate on test data.
* Model is tested on unknown image to test its accuracy for practical implementation.

