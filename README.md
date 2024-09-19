# CNN_Image_Classification
This project demonstrates the creation and training of a basic Convolutional Neural Network (CNN) to classify images. The CNN model is designed to identify and categorize images, utilizing GPU acceleration to enhance training efficiency.

# Simple Image Classification Project

## Overview

The **Simple Image Classification** project is designed to demonstrate the process of building a basic convolutional neural network (CNN) for image classification tasks. This project aims to address a classic problem in machine learning by classifying images into predefined categories using a neural network model.

## Project Objectives

1. **Understand Image Classification**: Learn the fundamentals of image classification, a common task in machine learning that involves predicting the category of an image based on its content.
2. **Build a Convolutional Neural Network (CNN)**: Develop a simple CNN model to automatically recognize and classify images from a dataset.
3. **Utilize GPU Acceleration**: Optionally, leverage GPU computing to speed up the training process of the neural network, using CUDA if available.

## Dataset

For this project, we use the CIFAR-10 dataset, a well-known dataset in the machine learning community. It contains 60,000 32x32 color images categorized into 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset is split into 50,000 training images and 10,000 test images.

## Key Components

1. **Data Loading and Preprocessing**:
   - Load the CIFAR-10 dataset.
   - Normalize image pixel values for better model performance.
   - (Optional) Display sample images to understand the dataset.

2. **Model Building**:
   - Construct a Convolutional Neural Network (CNN) with multiple convolutional and pooling layers.
   - Add dense layers to make predictions based on extracted features.

3. **Model Training**:
   - Train the CNN using the training data.
   - Evaluate the model performance using validation data.

4. **Model Evaluation**:
   - Assess the trained model on the test dataset to determine its accuracy and effectiveness.

5. **GPU Acceleration (Optional)**:
   - If a CUDA-compatible GPU is available, configure TensorFlow to use GPU resources, which can significantly reduce training time.
   - If else a AMD-compatible GPU is available, configure Keras to use Plaidml backend with Opencl to aply GPU acceleration. Look this link: [Maximiza el potencial de tu entrenamiento de modelos con GPU Acceleration](https://www.linkedin.com/pulse/maximiza-el-potencial-de-tu-entrenamiento-modelos-con-zubieta-pe%C3%B1a-k2m1c/)

## Contact

For any inquiries or feedback, please contact:

- **Email**: [ena.ateibuz@gmail.com](ena.ateibuz@gmail.com)
- **LinkedIn**: [ana-zubieta](www.linkedin.com/in/ana-zubieta)

Thank you for exploring this project. Happy coding!


