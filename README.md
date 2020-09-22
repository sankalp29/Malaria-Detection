# Malaria-Detection
A Convolutional Neural Network model trained on 27,558 images of positive and negative cell images used to detect whether or not a person is suffering from Malaria.
The initial steps involved pre-processing of data(images) available in 2 folders namely - Parasitized and Uninfected.
The dataset was formed by accessing the folder with images using the OS module, iterating on each image, resizing it to a specific value, and finally converting it into a NumPy array.
A dataset of Labels was formed by appending the corresponding label of the image, i.e Parasitized or Uninfected (0 or 1).
The entire dataset was then passed through a Convolutional Neural Network with Convolutional layers, Max Pooling layers, Batch Normalization and Dropout to prevent overfitting.
These layers were followed by 3 dense layers with the final layer having a Sigmoid Activation Function (0 or 1).
The optimizer used is Adam and the Cost function is Categorical Cross Entropy.
Trained with an accuracy of 97.63% and a validation accuracy of 95.15%.

