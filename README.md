# MRI Brain Tumor Classification using Ensemble Method

## Overview
This project aims to classify MRI brain images into four categories of tumors: 'meningioma', 'glioma', 'pituitary', and 'notumor', using a combination of multiple pre-trained deep learning models. The ensemble method is utilized to combine the predictions of various models. This approach leverages the strengths of each model and improves overall classification performance.

## Dataset Explanation
The dataset consists of MRI (Magnetic Resonance Imaging) brain scans along with corresponding labels indicating the type of tumor present in each scan. There are 3 categories of tumors in the dataset: 'meningioma', 'glioma', 'pituitary', and 'notumor'. Each MRI scan is associated with one of these tumor types or labeled as 'notumor' if no tumor is present.

## MRI Brain Scans
MRI brain scans are medical imaging techniques that use strong magnetic fields and radio waves to generate detailed images of the brain's internal structures. Each MRI scan is a 3D volume representation of the brain, providing information about the brain's anatomy.

## Tumor Types
* Meningioma: Meningioma is a type of tumor that arises from the meninges, the protective membranes that surround the brain and spinal cord. It is usually benign, but it can cause symptoms depending on its size and location.

* Glioma: Glioma is a type of tumor that originates from glial cells, which are supportive cells in the brain. Gliomas can be benign or malignant and are associated with different levels of aggressiveness.

* Pituitary: Pituitary tumors develop in the pituitary gland, a small gland located at the base of the brain. These tumors can cause hormonal imbalances and other health issues.

* Notumor: This category indicates that the MRI scan does not show the presence of any tumor. It includes normal brain scans or scans with non-tumor-related abnormalities.

## Data Split
The dataset is divided into three subsets for training, validation, and testing purposes:

* Training Set: This subset contains a large portion of the data and is used to train the deep learning models.

* Validation Set: The validation set is used to fine-tune hyperparameters and evaluate the models during training to prevent overfitting.

* Test Set: This subset is kept separate from the training and validation sets and is used to evaluate the final performance of the trained models. It simulates real-world data that the models have not seen during training.

## Transfer Learning models used were:
* VGG16
* VGG19
* InceptionV3
* ResNet50
* Inception ResNet V2
* DenseNet201
* ResNet101
* MobileNet
* Xception
* ResNet152

After training our data with all the models the accuracy of all the models is obtained and the ones giving the best accuracy were chosen to perform the Ensemble method. 
