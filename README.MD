# Image Classification using Convolutional Neural Network (CNN)

<a align='center' href="https://imgbb.com/"><img src="https://i.ibb.co/BGyWSYp/images.jpg" alt="images" border="0"></a>

This repository contains a Jupyter Notebook focused on image classification using Convolutional Neural Networks (CNN). The project utilizes the Kaggle Cat vs Dog dataset to train a CNN model to distinguish between images of cats and dogs.

## Overview
The goal of this project is to build a deep learning model capable of accurately classifying whether an input image contains a cat or a dog. CNNs are particularly effective for image classification tasks due to their ability to capture spatial hierarchies and patterns in images.

## Dataset
The dataset used in this project is the Kaggle Cat vs Dog dataset, which can be accessed [here](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset). It consists of thousands of labeled images of cats and dogs. The images vary in terms of breed, size, and orientation, providing a diverse set for training and testing the model.

## Usage
1. **Clone the repository:**
    ```bash
    git clone https://github.com/mohammadreza-mohammadi94/Image_Classification_Convolutional_Neural_Network.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Image_Classification_Convolutional_Neural_Network
    ```
3. **Download the dataset:**
   - Download the Kaggle Cat vs Dog dataset from [Kaggle](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset).
   - Extract the dataset files into a folder named `dataset` within the project directory.

4. **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook Convolutional_Nerual_Network.ipynb
    ```

## Key Steps
- **Data Preprocessing:** Loading images, resizing, and normalizing pixel values.
- **CNN Architecture:** Designing and building a convolutional neural network using TensorFlow/Keras.
- **Model Training:** Compiling the model, specifying loss function and optimizer, and training the model on the dataset.
- **Evaluation:** Assessing model performance using accuracy metrics and visualizing results.
- **Prediction:** Making predictions on new images using the trained model.

## Dependencies
- Python
- Jupyter Notebook
- TensorFlow
- Keras

Install the required packages using:
```bash
pip install tensorflow matplotlib keras jupyter
```

## Results
The project results in a trained CNN model that achieves high accuracy in classifying images of cats and dogs. Performance metrics and visualizations are provided to evaluate the model's effectiveness.

## Conclusion
This project demonstrates the application of CNNs for image classification tasks using TensorFlow/Keras. The trained model can be further optimized or extended for more complex image recognition tasks or integrated into applications requiring automated image classification.