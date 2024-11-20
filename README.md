# Project I | Deep Learning: Image Classification with CNN

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 categories (airplanes, cars, birds, cats, etc.), with 50,000 training and 10,000 test images. More details can be found [here](https://www.cs.toronto.edu/~kriz/cifar.html).

## Project Structure

- `v1/`: Contains previous attempts and experimental models.
- `v2/`: Contains the most recent and refined version of the CNN model.

## Model

The CNN includes:

- Convolutional layers for feature extraction
- Max pooling for downsampling
- Dropout to prevent overfitting
- Batch normalization
- Fully connected layers with softmax activation

## Preprocessing

- Normalize pixel values to [0, 1]
- One-hot encode labels
- Apply data augmentation (rotation, zoom, flip)

## Training

- Optimizer: Adam
- Loss: Categorical Crossentropy
- Metrics: Accuracy, Precision, Recall
- Learning rate scheduler to adjust during training

## Evaluation

Model performance is evaluated on the test set using accuracy, precision, recall, and a confusion matrix.

## How to Run

### Prerequisites

```bash
  pip install -r requirements.txt
```
