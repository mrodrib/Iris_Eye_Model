# Iris Eye Model

This project's objective has been to create an artificial intelligence model that helps in the identification of colors.

A [web application](https://github.com/LorenaDeveloper/Iris-Eye/) has also been created for its use.

A balanced dataset (70 images per class) of 11 colors has been used. (available in the repository)

# Table of contents
* [Iris-Eye](#iris-eye-model)
* [Table of contents](#table-of-contents)
* [General info](#general-info)
* [Technologies](#technologies)
* [Spacific info](#specific-info)
* [Status](#status)
* [Contact](#contact)


# General info

Date: December 2021

Duration: 2 weeks

It's part of _"III CURSO DE EXTENSIÓN UNIVERSITARIA SAMSUNG INNOVATION CAMPUS EN INTELIGENCIA ARTIFICIAL (2021-22)"_ taught by the University of Malaga

# Technologies
* Python
* Tensorflow
* Keras Tuner
* CV2
* sklearn

# Specific info

We've used a Keras convolutional network optimized with Keras Tuner. As well as a callback function to get best weights training.

Best accuracy achieved was 0.9792.

The final model is composed of two 2D convolutional layers behind which there are reduction or max_pooling layers. 

Behind the convolutional layers is a flatten layer that performs the transformation of 3D matrices to 1D tensors that will be the input to the dense output layers, between which a dropout layer is placed (although in the final model the optimal dropout index is set to 0).

![image](https://user-images.githubusercontent.com/81416550/147597492-0623b2de-e4a0-4b46-ae43-1efa49d6a817.png)

<br><br>

We can observe how the model during training adjusts rapidly from the first periods, without producing large oscillations or overfitting.

<img width = '1000px' src="https://user-images.githubusercontent.com/81416550/147597543-7ff71177-f77b-48d8-95fc-2ff25914ff4d.png">

<br><br>

The roc (Receiver Operating Characteristic) curve shows that the model performs very well in classifying the different colors.
This plot plots the false positive ratio (x-axis) against the false negative ratio (y-axis).

<img width = '500px' src="https://user-images.githubusercontent.com/81416550/147597754-7a21db04-e3a0-475b-adab-b5495e4c0b80.png">

<br><br>

The confusion matrix of the model indicates that it has a high level of accuracy in classifying the different colors.

The main diagonal shows the correctly predicted images for each of the classes (colors) of the test set.

<img width = '500px' src="https://user-images.githubusercontent.com/81416550/147597840-421b0efc-b7af-4225-a8f1-0703396051f0.png">


# Setup

Clone/Download repository
```sh
https://github.com/LorenaDeveloper/Iris_Eye_Model.git
```


# Status
Proyect is : _Completed_

# Contact
Created by [@Lorena](https://www.linkedin.com/in/lorena-jiménez-tejada-966611176), fell free to contact me! In collaboration with [@Mercedes Rodríguez](https://www.linkedin.com/in/mercedes-rodriguez-barbero-20ab3766), [@Marta Trasancos](https://www.linkedin.com/mwlite/in/marta-trasancos-09178063), [@Marta Freire](https://www.linkedin.com/in/marta-freire-painceira-8ba76025) and [@Marina Jiménez](https://www.linkedin.com/in/marinajimenezegea)
