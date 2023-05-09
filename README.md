# Malaria-Detector-Using-ResNet50
This repository contains code for a malaria detection system using a pre-trained ResNet50 model on TensorFlow. The model is trained to detect malaria parasites in cell images.

# Installation
This code requires the following libraries:

tensorflow

google-colab

To install the libraries, run the following command:

!pip install tensorflow google-colab

# Usage
Clone the repository or download the code as a .py file.

Mount Google Drive using the command: drive.mount('/content/drive')

Extract the dataset zip file using the code provided in the script.

Run the script and the model will start training.

After the training is complete, the model will be saved as model.h5.

# Results
After training the model for 10 epochs, the accuracy on the validation set was 0.9512 and the loss was 0.1306. The model was saved as model.h5.

# Acknowledgments
The dataset used in this project was obtained from the [Malaria Cell Images Dataset](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria) on Kaggle.

The ResNet50 model used in this project was pre-trained on the ImageNet dataset.
