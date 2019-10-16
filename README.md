# Soybean-Leaf-Wilting-CNN

The aim of this project is to detect leaf-wilting level from images of Soybean crops.

The training dataset contains about 900 colored images in 480X640 resolution.


## File Description

- [optimize](optimize.py)
    This is the main file containing the code for manually tuning the hyperparameters. Separate functions are called for each parameters. These functions train models for each of the provided values and generate plots to demonstrate the results. The user need to close the plots and provide the selected value at the terminal.

- [data4projC](data4projC.py)
    This file reads the list of data files and labels from a CSV file. Then it reads those images and preprocesses/splits them into training, validation, and testing datasets.

- [model4projC](model4projC.py)
    This file creates the CNN network model from the [TensorFlow Sequential API](https://www.tensorflow.org/api_docs/python/tf/keras/Sequential) and sets the training configuration.
    
