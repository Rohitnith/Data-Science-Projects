# Upgrad_Melonoma
> To build a multiclass classification model using a custom convolutional neural network in TensorFlow which can accurately detect melanoma.

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
- From the M1 model it can be seen that model is over fitting since as with increase in the epoches training accuracy is increasing but validation accuracy is not increasing and is somewhat peaked out.
- We can see in Model M2 there is an issue of underfitting as train accuracy is only ~0.55, therfore further investigation of data is required to find out reason for low train accuracy.
- From the Model M3, Class rebalance has helped to increase accurcacy from ~58 to 80 using the class rebalance technique and model is not overfitting..



## Technologies Used
- TensorFlow 
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

