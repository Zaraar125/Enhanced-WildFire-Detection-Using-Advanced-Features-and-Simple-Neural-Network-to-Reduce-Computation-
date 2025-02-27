# Enhanced Wild Fire Classification

## Project Overview
The Enhanced Wild Fire Classification project focuses on utilizing Convolutional Neural Networks (CNNs) to classify and detect wild fires in images. The project aims to enhance the classification accuracy by incorporating advanced features such as Local Binary Patterns (LBP), Histogram of Oriented Gradients (HOG), and Image Histograms, while also leveraging a simpler Neural Network (NN) model to reduce computational costs associated with CNNs.

## Precious Approach
The previous approach involved using CNNs for wild fire classification and detection. While CNNs are powerful for image recognition tasks, they can be computationally expensive, especially for large datasets or real-time applications.

## My Approach
My approach combines the power of advanced image features such as LBP, HOG, and Image Histograms with a simpler Neural Network model. This hybrid approach aims to achieve desirable classification results while reducing computational overhead. By extracting meaningful features from images and then training a simple NN model, we can achieve efficient and accurate results.

## Key Features
- Utilizes LBP, HOG, and Image Histograms for feature extraction.
- Trains a simple Neural Network model for classification.
- Aims to reduce computational costs compared to pure CNN approaches.
- Enhances classification accuracy for wild fire detection in images.

## Installation
1. Clone the repository: https://github.com/Zaraar125/Enhanced-WildFire-Image-Classification.git
2. Dataset has been collected from the following link's :
3. https://www.kaggle.com/datasets/atulyakumar98/test-dataset
4. https://www.kaggle.com/datasets/phylake1337/fire-dataset
5. https://github.com/DeepQuestAI/Fire-Smoke-Dataset?tab=readme-ov-file
## Usage
1. Download dataset of wild fire images .
2. The feature extraction of LBP, HOG, and Histogram features from the images is being executed in batches in the ipnyb file.
3. Train the Neural Network model using the extracted features.
4. Evaluate the model's performance and adjust hyperparameters as needed.
5. Use the trained model for wild fire classification tasks.
