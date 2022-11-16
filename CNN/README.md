# Upgrad_Melonoma
> To build a multiclass classification model using a custom convolutional neural network  which can accurately detect Melanoma.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- From the M1 model it can be seen that model is over fitting since as with increase in the epochs training accuracy is increasing but validation accuracy is not increasing and is somewhat peaked out, reason for same could be less data as we know CNN requires a lot of data for training.
- We can see in Model M2 there is an issue of underfitting as train accuracy is only ~0.53, therfore further investigation of data is required to find out reason for low train accuracy which may be due to class imbalance.
- From the Model M3, Class rebalance using the Augmentor library has helped to increase validation accurcacy from ~50 to 82 and model is not overfitting. One important fact to notice here is that till approx. 25 epochs validation acc. is more than training acc., which may be due to implementation of dropouts during training which are not implemented while testing model.



## Technologies Used
- TensorFlow 
- Keras
- Matplotlib
- Pandas
- Numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.
- This project was based on [this tutorial](https://learn.upgrad.com/course/1989/segment/24863/153448/470991/2438926).


## Contact
Created by [@Rohitnith] - feel free to contact me! - 
rohitc.nith@gmail.com

