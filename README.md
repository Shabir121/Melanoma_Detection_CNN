# Melanoma Detection Assignment using CNN

   

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

## Problem Statement
  Need to build a CNN based model which can accurately detect melanoma skin cancer. 

  Melanoma is a type of cancer that can be deadly if not detected at early stage.
  It accounts for about 75% of skin cancer death.

  A machine learning solution  for this which can evaluate images and alert the
  dermatologists about the presence of melanoma.
  It has the potential to reduce a lot of manual effort needed in diagnosis it which can result in maximum profit.

  Goal:-   
  Need to build a multiclass classification model using a custom convolutional  neural network using TensorFlow.


## Approach
  We will build a baseline of CNN model first and tune it on using validation set.   

  We will check the presence of underfitting / overfitting in the  model and improve it using
  ***Augmentation*** of the training data.

  We will check for ***class imbalance*** in the dataset and improve it  by generating  more images of each classes.	


## Conclusions

  1. The model has achieved maximum train and validation  accuracy of 82% and 77 % respectively.
     


  2. Model is not overfitting  as their training and validation accuracy are closer.
     The accuracy for both training and validation decreased gradually with updating dataset and model.


  3. The loss for both training and validation decrease gradually together as well.


  4. We can conclude that  ***after reducing class imbalance***, ***accuracy has increases significantly*** and also **overfitting is under check**.


  5. Hence we can conclude that,the case where the number of training data is less, following method needs to be employed.

    Adding more data using augementation pipeline.


    Adding dropout layer to reduce overfitting.
   
   
    Adding Batch normalisation to achieve more accuracy.
    
    
    
## Technologies Used

    - pandas - version 1.2.4
	- numpy - version 1.20.1
	- seaborn - version 0.11.1
	- matplotlib - version 3.3.4
	- python - version 3.6.3
	- statsmodels.api - version 0.12.2
	- sklearn - version 0.24.1
    - Tensorflow version 2.8.0
    - Keras version 2.8.0
    
## Acknowledgements

    This project would not have been possible without UpGrad lectures and mentors support
        

## Contact
    Created by [@Shabir121] - feel free to contact me!

