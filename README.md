# Segmentic-Segmentation-using-UNet

## Project Objectives

1. **Model Development:** Develop a deep learning model capable of predicting semantic segmentations of images obtained from the CARLA self-driving car simulator.

2. **Semantic Mask Prediction:** The trained model is utilized to generate semantic masks for input images and then compared with ground-truth masks to assess its accuracy in identifying objects and their classes within the images.

## Dataset Overview

The dataset used in this project consists of images and corresponding labeled semantic segmentations, all of which were captured within the CARLA self-driving car simulator. This dataset, originally created as part of the 2018 Lyft Udacity Perception Challenge, comprises approximately 5000 images and their associated semantic segmentations.

## Model Evaluation

- **Training Accuracy:** After 30 epochs of training, the model achieves an impressive training accuracy of nearly 99%. This high training accuracy suggests that the model has effectively learned to segment objects within the training dataset.

- **Testing Accuracy:** The model demonstrates its ability to generalize well to unseen data by achieving a testing accuracy of nearly 94%. This high testing accuracy underscores the model's robustness and effectiveness in real-world scenarios.

- **Training:** During model development, the dataset is used to train the model over a specific number of epochs. Techniques such as batch normalization and dropout may be employed to prevent overfitting.

- **Evaluation:** Model performance is assessed using metrics such as accuracy and loss on both the training and testing datasets to gauge its effectiveness.

## Results and Predictions

The attached notebook provides a comprehensive exploration of the project, offering insights into the following areas:

- **Architecture Details:** Detailed information about the model architecture, including its structure and components.

- **Training Progress:** A breakdown of the model's training progress, including the number of epochs and the resulting accuracy.

- **Model Evaluation:** An examination of the model's performance on both training and testing datasets, highlighting its effectiveness in semantic segmentation tasks.

The project results demonstrate the model's capability to accurately predict semantic segmentations for self-driving scenarios, emphasizing its potential for real-world applications in autonomous vehicles.

This project serves as a valuable resource for individuals interested in semantic segmentation for self-driving applications, providing valuable insights into model development, training techniques, and evaluation procedures using real-world data obtained from the CARLA simulator.
