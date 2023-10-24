# Computational-Models-of-Cognition
Final Project for COS360: Computational Models of Cognition

The Memorable Image Generator is a machine learning project that uses a Generative Adversarial Network (GAN) to enhance the memorability of images. It utilizes a ResNet-based model to predict the memorability of images and a GAN structure to process and return more memorable images.

## Project Structure

- `model.py`: Contains the code for the memorability prediction model and the GAN (generator and discriminator).
- `train.py`: Contains the code to train the models.
- `utils.py`: Contains utility functions used throughout the project.
- `images/`: Directory where the image dataset should be placed.

## Getting Started

### Prerequisites

- Python 3.6 or later
- PyTorch
- torchvision
- NumPy
- PIL

You can install the required libraries using the following command:

```sh
pip install torch torchvision numpy pillow

