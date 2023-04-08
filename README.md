# American_Sign_Language_Classification
## General Background and Goals
Sign languages are visual languages that use hand gestures, facial expressions, and body language to convey some meaning. They are used as a means of communication by deaf and hard-of-hearing individuals in many countries around the world. Unlike spoken languages, sign languages are not based on a particular spoken language and are unique to the deaf communities in which they are used.

Despite the widespread use of sign languages, there is still much work to be done in improving communication between deaf and hearing individuals and the development of technologies that can recognize and understand sign languages is an important step towards this goal.

In our project, we are exploring the use of deep learning for American Sign Language (ASL) recognition by teaching our neural network to classify between different ASL letters. The dataset we are using is the ASL MNIST dataset, which is a dataset that has been adapted to specifically focus on the recognition of American Sign Language.

## Data Description
Our data composed from 28x28 grayscale images (one channel images), each one represents one of the 24 american letters that not require any motion, i.e all the american letters except J and Z.
The data contains 34,627 images in total and it devided into the following types:

1) Test and Validation data- 27,455 images
2) Test Data- 7,172 images

In addition, the first column of the data represents the labels of the images as a numeric values. We have in total 26 american letters that their labels are the numbers 0-25 correspondingly to the order of the letters, and because we are not using the letters J and Z (which require motion as we mentioned before) we have left only with the labels 0-8 and 10-24.

## Main Goal
We expect to achieve accuracy of 90% on the "Dataset test images" using the network we will create in the project.

## Additional Goal
In addition to the classification of the MNIST data itself, our goal in this project is to exemine the classification accuracy for images that were taken from our personal phones. Those images will have a different properties, due to the type of the camera, initial resolution and also the enviroment where the image were taken, thus we will expect to get lower accuracy for those kind of images.

## Different models compared in terms of their performances
1) Two different implementations of classical Convolutional Network
2) Residual Network
3) VGG

