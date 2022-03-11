# Multiclass-Image-Classification-
This project explains How to build a Sequential Model that can perform Multi Class Image Classification in Python using CNN

#Approach

- Importing the required libraries.
- Load and read the data images

## Data pre-processing
- Create train and validation data
- Normalize the data
- Reshape the data images
- Data augmentation
- Using ImageDataGenerator

## Model Training
- Create a sequential model
- Add convolution, maxpool,dropout layers
- Add the softmax activation function (As this is a multiclass classification problem)
- Pass the optimizer parameter
- Compile the model
- Fit and train the model

## Check for the predictions
- Save the model in h5 format.
- Inferencing the model
- Prediction on the test data
