# Vehicle Damage Detection

This project aims at identifying damages on a vehicle from its image. In this process, the use of Convolutional Neural Networks (CNN) was done. A Convolutional Neural Network is a class of deep neural network most commonly applied to analysing visual imagery.

## Project Description

In this project, Mask RCNN, a deep neural network was used. This was because the problem at hand is that of image segmentation (identifying the image of specific object) and Mask RCNN proves to be efficient at this task. For this project, 49 training and 15 testing images were chosen. The output was produced by this trained model by creating a coloured mask on the image at the location of damage. Also, the output confidence, that the masked section is damaged, is also displayed.

