# Dogs vs. Cats Image Classification

This project demonstrates an image classification task using a Convolutional Neural Network (CNN) to classify images of dogs and cats. The model is trained on the Dogs vs. Cats dataset.

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- Kaggle API Key (if using Kaggle datasets)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/anchal9670/dogs-vs-cats-Classification.git
   cd dogs-vs-cats
2. Download the Dogs vs. Cats dataset from Kaggle:
   ```sh
   pip install kaggle
   kaggle datasets download -d salader/dogs-vs-cats
   unzip dogs-vs-cats.zip -d dataset/

## Model Architecture

The CNN model consists of multiple convolutional layers, batch normalization, max-pooling, and fully connected layers. The architecture is defined in the `model.py` file.

## Results

After training for a certain number of epochs, the model achieves a validation accuracy of approximately XX%.


