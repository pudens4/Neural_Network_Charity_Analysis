# Neural_Network_Charity_Analysis

## Overview
The purpose of this project is to create a model that can predict whether or not applicants will 
get funding based on a binary classier created from the dataset

## Results: 

Application Type
![image](https://user-images.githubusercontent.com/86452750/147374537-b4e86b90-8fb7-4a45-a43b-a36c0fe6d392.png)

Classification
![image](https://user-images.githubusercontent.com/86452750/147374535-80554258-1855-4170-a9e4-55222b812e2d.png)


Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense (Dense)               (None, 80)                3600      
                                                                 
 dense_1 (Dense)             (None, 30)                2430      
                                                                 
 dense_2 (Dense)             (None, 1)                 31        
                                                                 
=================================================================
Total params: 6,061
Trainable params: 6,061
Non-trainable params: 0

Evaluation of the model

268/268 - 0s - loss: 0.8412 - accuracy: 0.3722 - 316ms/epoch - 1ms/step
Loss: 0.8411843776702881, Accuracy: 0.3722448945045471


## Summary: 
