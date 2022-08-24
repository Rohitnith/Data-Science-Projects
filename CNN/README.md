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
- From the M1 model history graphs we can clearly observe that our model is **over fitting** since as you increase the epoches we can see the training accuracy is increasing but validation accuracy is staying down.
- We can see in Model M2 we introducded augmented layer and Dropout layers and also we removed Overfitting because training and validation accuracy is nearly same across all the epoches but main problem is accuracy is not good , so we will now deal with one common problem named class imabalance.
- From the Model M3, Class rebalance helped so much that our accuracy is increased from 60 to 80 using the class rebalance technique . From above graph we can also observe that at 20 epoches our model is stabilized, beyong 20 epoches our model is overfitting.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow - version 2.8
- Matplotlib
- Pandas
- Numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.
- This project was based on [this tutorial](https://learn.upgrad.com/course/1989/segment/24863/153448/470991/2438926).


## Contact
Created by [@loksundar] - feel free to contact me! - loksundar000@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
