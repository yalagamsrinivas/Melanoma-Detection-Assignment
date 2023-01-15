<h1> Melanoma-Detection-Assignment </h1> 
Brief description of the project:

- In this assignment, you will build a multiclass classification model using a custom convolutional neural network in TensorFlow.  

## Problem statement: 

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## General Information:

- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion


## Conclusion from Melanoma-Detection-Assignment:

- Class balacing with Augmentor helped to create 500 more samples for each class, and model is trainined on augmented and class balanced data.
- Training and Validation accuracy increases with epochs,training and validation loss decreases with epochs.
- Train data accuracy is 91.39, validation data accuracy is 80.47 and test data accuracy is 34.44.
- Current model achieves good performance on train and validation datasets and resonable performance in test data.
- Augmentor class balancing strategy achieved better results than ImageDataGenerator augmentation strategy.
- Tried with different combination of layers, ex: dropout, batch normalization etc.
- As train dataset is very limited, it requires more diverse dataset to get good performanc on test dataset.
- Overall model achived good fit on train and validation datasets.


## Technologies Used:

- pandas - version 1.2.4
- numpy - version 1.20.1
- seaborn - version 0.11.1
- matplotlib - version 3.3.4
- scikit-learn - version 1.0.2
- statsmodels - version 0.13.2
- tensorflow 2.9.2
- keras - 2.9.0
- Augmentor - 0.2.9
- glob2 - 0.7
- Pillow - 7.1.2

## Acknowledgements:
Give credit here.
- This project was inspired by Upgrad(IIITB) Melanoma-Detection-Assignment.


## Contact:
Created by [@yalagamsrinivas] - feel free to contact us!

