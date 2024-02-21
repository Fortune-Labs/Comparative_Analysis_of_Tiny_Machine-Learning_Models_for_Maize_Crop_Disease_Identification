# Comparative Analysis of Tiny Machine Learning Models for Maize Crop Disease Identification

This repository presents a comparative analysis of tiny machine learning models for maize crop disease identification. The project focuses on leveraging various lightweight models to accurately classify different diseases affecting maize crops.

## Authors

## Datasets
The Datasets directory contains the "MaizeDiseaseImage_Classification_Dataset_Ghana," which includes images of maize crops affected by various diseases. The dataset is organized into five directories:

* Blight
* Common_rust
* Grapy_leaf_spot
* Healthy
* Streak_virus

Each directory contains images corresponding to the respective maize crop diseases

#### Sample Images
![alt text](hhttps://github.com/Fortune-Labs/Comparative_Analysis_of_Tiny_Machine-Learning_Models_for_Maize_Crop_Disease_Identification/blob/master/images/leaves.png?raw=true)

## Models
The models directory encompasses six subdirectories, each dedicated to a specific tiny machine learning model:

* dnn
* efficientnet
* inception
* mobilenet
* shufflenet
* squeezenet
Within each model directory, you'll find the trained models and TensorFlow Lite (TFLite) files.

### Model Descriptions:
1. DNN: Represents a basic deep neural network.
EfficientNet: Utilizes the EfficientNet architecture for efficient image classification.
2. Inception: Implements the Inception architecture known for its utilization of inception modules.
3. MobileNet: Employs the MobileNet architecture optimized for mobile and embedded vision applications.
4. ShuffleNet: Utilizes the ShuffleNet architecture designed for efficient model inference.
5. SqueezeNet: Implements the SqueezeNet architecture, emphasizing smaller model size and faster inference.
### How to Use
Dataset Preparation: Ensure the "MaizeDiseaseImage_Classification_Dataset_Ghana" dataset is properly organized in the Datasets directory.

Model Selection: Choose the desired tiny machine learning model from the models directory based on your requirements for model size, inference speed, and accuracy.

Model Training: Train the selected model using the provided dataset or your custom dataset, depending on your specific maize crop disease identification requirements.

Model Evaluation: Evaluate the trained model's performance using appropriate evaluation metrics, such as accuracy, precision, recall, and F1 score, to assess its effectiveness in identifying maize crop diseases.

Model Deployment: Deploy the trained model to your desired platform or device for real-time maize crop disease identification and monitoring applications.

## Contributions
Contributions to this project are welcome. If you have any improvements, bug fixes, or additional models to contribute, feel free to submit a pull request.

## License