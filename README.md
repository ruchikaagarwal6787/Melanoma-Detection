# Melanoma-Detection
> A multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The project is about classification of different types of skin diseases and identity melanoma through AI and specifically CNN.
- The business problem is to build a CNN based model which can accurately detect melanoma skin cancer.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis/n
Basal cell carcinoma/n
Dermatofibroma/n
Melanoma/n
Nevus/n
Pigmented benign keratosis/n
Seborrheic keratosis/n
Squamous cell carcinoma/n
Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model Overfitting can be reduced by adding Dropout Layers
- We should choose an appropirate optimiser and loss function for model training.
- Underfitted Model needs to be made more complex.
- Proper Augmentor Strategy can rebalance the imbalances classes in the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.11.7
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Tensorflow - version 2.18.0
- Keras - version 3.6.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is an assignment given by UPGRAD's AI/ML Course.


## Contact
Created by [ruchikaagarwal6787] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
