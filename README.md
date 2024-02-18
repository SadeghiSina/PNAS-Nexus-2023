# PNAS Nexus-2023:
## Dataset: The dataset used to develop and evaluate the CNN model. We have two classes with a balanced number of images; each class includes 3200 images.
## Train_CNN.ipynb: The Python code written to develop and evaluate the CNN model.
## User_Friendly.ipynb: The Python code that enables user to apply the developed CNN model on the unseen images. This code classifies unseen images into two categories and stores them into 2 different subdirectories based on the predicted labels.
### model_T.h5: The CNN model trained using the training set, which was subsequently applied on the validation set.
### model_TV.h5: The CNN model trained using both training and validation sets, which was subsequently applied on the test set.
### model_TVT.h5: The CNN model trained using the whole data set, which was subsequently applied to automatically classify unseen images.
