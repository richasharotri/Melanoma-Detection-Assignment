# Project Name
>  Project Name is Melanoma-Detection-Assignment
>  github directory name : @richasharotri/Melanoma-Detection-Assignment 
>  python code file name : Melanoma-Detection-Assignment-RichaSharma.ipynb

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- In this assignment, you will build a multiclass classification model using a custom convolutional neural network in TensorFlow.
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- Data set includes images of the 9 types of skin cancer divided into traning and testing data set
      The data set contains the following diseases:
       - Actinic keratosis
       - Basal cell carcinoma
       - Dermatofibroma
       - Melanoma
       - Nevus
       - Pigmented benign keratosis
       - Seborrheic keratosis
       - Squamous cell carcinoma
       - Vascular lesion


## Conclusions
- Finding on the first base model
    The model is overfitting because we can also see difference in loss functions in training & test around the 5th epoch
    The accuracy is just around 75% because there are enough features to remember the pattern.
    Maybe by doing some changes in the model we can get better results to understand if it's overfitting or underfitting

- Findings from Second Model
    Acuracy have not improved, infact it has declined but problem of overfitting is not there anymore because of data augmentation
    Maybe if we do some more chagnes in the model we may get better results
    
- Findings from Third Model
    Accuracy on training data has clearly increased by using Augmentor library
    Model is again still overfitting
    The problem of overfitting can be handled by adding more layer, neurons, adding dropout layers or by tuning the hyperparameter


## Technologies Used
- python 3.0


## Contact
Created by [@richasharotri] - feel free to contact me!


