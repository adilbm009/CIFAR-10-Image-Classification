# CIFAR-10 Image Classification

## Description

This project implements a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset using TensorFlow and Keras. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

The code loads the CIFAR-10 dataset, preprocesses the input images, builds a CNN model using Keras, and trains the model on the training set. After training, the model's performance is evaluated on the test set, and the training history is displayed.

## Installation

To run the project, make sure you have the following installed:

- Python (version 3.7 or above)
- TensorFlow (`pip install tensorflow`)
- Keras (`pip install keras`)

## Usage

1. Clone the repository:

git clone https://github.com/adilbm009/CIFAR-10-Image-Classification.git

2. Change into the project directory:

cd cifar10-image-classification

3. Run the script:

bash
python image_classification.py

The script will automatically download the CIFAR-10 dataset, preprocess the images, build the CNN model, and start training.

After training completes, the model's accuracy and loss on the test set will be displayed.

### Customization
To modify the CNN architecture, you can adjust the layers, their parameters, or add additional layers in the image_classification.py script.

To change the training settings, such as batch size or number of epochs, modify the respective parameters in the model.fit() function.

Feel free to experiment with different hyperparameters, data augmentation techniques, or regularization methods to improve the model's performance.

### Contributing
Contributions to the CIFAR-10 Image Classification project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
