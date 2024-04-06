# CNN Dog vs Cat Classification Model

This repository contains a Convolutional Neural Network (CNN) model for classifying images of dogs and cats. The model is trained on a dataset of 10,000 labeled dog and cat images (8,000 are used for training / 2,000 - for testing). The model quite accurately can predict whether an input image contains a dog or a cat.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/JustinasLasinskas/cnn-dog-vs-cat.git
   ```

2. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset by organizing the images into separate folders for dogs and cats (you can add more folders in case there are more classes). The dataset is not provided in this repo.

2. Run the Jupyter notebook to create, train and test the model

3. Make a prediction using your own image of a cat or a dog.

## Model Architecture

The CNN model architecture consists of two convolutional and pooling layers, followed by fully connected layer. We use Tensorflow to build the CNN model.

## Results

The model achieved an accuracy of 80% on the test dataset.

## MIT License

The MIT License is a permissive open-source license that allows you to use, modify, and distribute the code in both commercial and non-commercial projects. It also provides you with the freedom to sublicense the code under different terms if needed.
