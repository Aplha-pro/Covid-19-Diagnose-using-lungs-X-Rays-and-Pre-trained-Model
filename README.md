# COVID-19 Diagnose CNN Model

This notebook implements a Convolutional Neural Network (CNN) for diagnosing COVID-19 using a dataset of chest X-ray images. The CNN model is built using the Keras library with a TensorFlow backend.

## Overview

The notebook consists of the following main components:

1. **Image Preprocessing:**
   - The dataset is divided into training and testing sets.
   - ImageDataGenerator is utilized for data augmentation to enhance the model's performance.

2. **CNN Model Creation:**
   - A Sequential model is created using Keras.
   - Two Convolutional layers with MaxPooling layers and a Flatten layer are added.
   - Two Dense layers are added for classification.
   - The model is compiled with the Adam optimizer and categorical crossentropy loss.

3. **Training the Model:**
   - The model is trained using the training dataset with 25 epochs.
   - Training progress and validation accuracy are monitored and displayed.

4. **Evaluation:**
   - The trained model is evaluated on the testing dataset to assess its accuracy.
