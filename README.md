# Melanoma Detection using CNN
> The main aim of this project is to build a CNN based model which can accurately detect melanoma which is a type of cancer that can be deadly if not detected early.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Problem Solving Methodology](#problem-solving-methodology)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 

A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Problem Solving Methodology
* Data Reading & Understanding -
> Defining the path for train and test images.
* Dataset Creation -
> Create train & validation dataset from the train directory with a batch size of 32.
* Dataset visualisation -
> Visualize one instance of all the nine classes present in the dataset.
* Model Building & training -
> Create and train a CNN model, which can accurately detect 9 classes present in the dataset.
* Data Augmentation -
> Choose an appropriate data augmentation strategy to resolve underfitting/overfitting. Then, again create and train a CNN model, which can accurately detect 9 classes present in the augmented dataset
* Handling class imbalances -
> Rectify class imbalances present in the training dataset with Augmentor library.Then, again create and train a CNN model, which can accurately detect 9 classes present in the rectified class imbalance data.


## Conclusions
- The CNN model built on the rectfied class imbalance data gives around 93% training accuracy & 85% validation accuracy.

- Handling class imbalance and introducing batch normalization and dropouts have increased accuracy as well as removed overfitting upto an extent.


## Technologies Used
- Numpy        - version 1.21.6
- Pandas       - version 1.3.5
- Seaborn      - version 0.11.2
- Matplotlib   - version 3.2.2
- Tensorflow   - version 2.11.0
- Augmentor    - version 0.2.10
