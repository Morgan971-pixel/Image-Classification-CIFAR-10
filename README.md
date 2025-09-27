# Image Classification with CIFAR-10

This project demonstrates how to build and train a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset.

## Dataset

The CIFAR-10 dataset is a widely used benchmark dataset in machine learning and computer vision. It consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 test images.

The 10 classes are:

*   Airplane
*   Automobile
*   Bird
*   Cat
*   Deer
*   Dog
*   Frog
*   Horse
*   Ship
*   Truck

## Methodology

The notebook covers the following steps:

1.  **Data Loading:** The CIFAR-10 dataset is loaded directly from the `tensorflow.keras.datasets` module.
2.  **Data Preprocessing:** The pixel values of the images are normalized to be between 0 and 1.
3.  **Model Building:** A Convolutional Neural Network (CNN) is built using the Keras API from TensorFlow.
4.  **Model Training:** The CNN is trained on the training set of the CIFAR-10 dataset.
5.  **Model Evaluation:** The trained model is evaluated on the test set to assess its performance.

## Getting Started

### Prerequisites

*   Python 3
*   Jupyter Notebook or JupyterLab

### Installation

1.  Clone this repository:
    ```bash
    git clone <repository_url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd Image_Classification-CIFAR_10
    ```
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  Open the Jupyter notebook:
    ```bash
    jupyter notebook Image_Classification-CIFAR_10.ipynb
    ```
2.  Run the cells in the notebook to train the model and see the results.