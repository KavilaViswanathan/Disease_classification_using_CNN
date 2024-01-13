# Disease Classification Using CNN for Bell Pepper, Tomato, and Potato

## Introduction

In agriculture, early disease detection is critical for maintaining crop health and maximizing yields. This project employs Convolutional Neural Networks (CNN) to classify diseases in three key crops: Bell Pepper, Tomato, and Potato. By leveraging advanced machine learning techniques, the model aims to provide accurate and prompt identification of diseases, facilitating proactive measures for farmers.

## Table of Contents

- [Introduction](#Introduction)
- [Features](#features)
- [Dataset](#Dataset)
- [Requirements](#Requirements)
- [Example Output](#example-output)
- [Conclusion](#conclusion)

## Features

- **Multi-Crop Classification:**
  - Detects diseases in Bell Pepper, Tomato, and Potato crops.

- **Convolutional Neural Network (CNN):**
  - Utilizes a CNN architecture for effective image-based disease classification.

- **Real-time Classification:**
  - Enables quick and accurate identification of diseases in real-time scenarios.

- **Diverse Dataset:**
  - Trained on a diverse dataset featuring images of healthy plants and various disease manifestations.

## Dataset

The dataset used for this project is available on Kaggle: [Plant Village Dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village). Follow the instructions on Kaggle to download and use the dataset.

## Requirements

Ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## Example Output

Below are examples of disease classifications made by the trained CNN model on sample images of Bell Pepper, Tomato, and Potato plants:

### Bell Pepper
#### Input Image:
![Bell pepper image](https://github.com/KavilaViswanathan/Disease_classification_using_CNN/assets/140960627/58440c7d-b700-4f13-bb55-d8879df8b963)


#### Model Prediction:

Disease: Bacterial Spot

Confidence: 100.0

### Tomato

#### Input Image:
![Tomato Image](https://github.com/KavilaViswanathan/Disease_classification_using_CNN/assets/140960627/00dbf416-fc00-4b8f-a281-1f37143c8619)


#### Model Prediction:

Disease: Late Blight

Confidence: 100.0

### Potato

#### Input Image:
![Potato Image](https://github.com/KavilaViswanathan/Disease_classification_using_CNN/assets/140960627/afa2ea55-f462-428d-a716-4ac4b269168d)


#### Model Prediction:
Disease: Late Blight
Confidence: 100.0


These examples demonstrate the model's ability to accurately classify diseases in various crops. Include images, predicted diseases, and confidence scores to provide a visual representation of your model's performance. Ensure the paths to the images are correct and replace the placeholder text with actual disease predictions and confidence scores.

## Conclusion

This utilizes CNNs for crop disease classification, aiming to revolutionize early detection, empower farmers, and enhance global food security.


