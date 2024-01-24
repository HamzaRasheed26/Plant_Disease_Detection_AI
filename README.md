# AI-Powered Crop Disease Detection System

## Abstract
Crop diseases pose a significant threat to food security in Pakistan. This project aims to develop an AI-powered crop disease detection system that is accurate, efficient, and accessible to farmers. The system will be trained on a diverse dataset of labeled leaf images, enabling it to identify and classify diseases with high accuracy.

## Acknowledgments
Special thanks to Mr. Samyan Qayyum Wahla for guidance and support, and the Department of Computer Science at the University of Engineering and Technology, Lahore.

## Introduction
Crop diseases lead to substantial losses in the Pakistani agricultural sector. This project introduces an AI-powered solution for timely and accurate disease detection.

## Problem Statement
Traditional methods of disease detection are time-consuming and often involve expensive laboratory testing. The shortage of trained plant pathologists further hinders timely and accurate disease detection.

## Proposed Solution
The AI-powered system aims to provide quick and accurate diagnoses of crop diseases, even in remote areas. Accessible via smartphones, the system assists farmers in identifying diseases early.

## Methodology
The system uses deep learning with a Convolutional Neural Network (CNN). The dataset is sourced from Kaggle and undergoes pre-processing, including resizing, normalization, and augmentation. The trained model is evaluated on a test set to assess its performance.

### Data Collection
The dataset includes images of various crop species and disease types, ensuring representativeness. [Link to dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)

### Data Pre-processing
Images undergo resizing, normalization, and augmentation to enhance the dataset's diversity and prepare it for training.

### Model Training
A CNN is employed for training, using the Keras Sequential API.

### Model Evaluation
The trained model is evaluated on a test set using metrics such as accuracy, precision, and recall.

## Expected Results
The project anticipates the development of an accurate, efficient, and user-friendly crop disease detection system accessible to farmers across Pakistan.

## System Architecture
The system consists of data input, pre-processing, CNN, user interface, and output components. It aims for a seamless flow of data and operations.

## Results and Discussion
The system shows promising results, demonstrating high accuracy in identifying and classifying crop diseases. User interface design for smartphones is well-received.

## Conclusion
The AI-powered Crop Disease Detection System holds significant potential in improving crop management practices in Pakistan. Challenges include image quality dependency and dataset bias. Continued efforts are needed for practical implementation.

