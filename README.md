# CT to MRI Image Translation using Deep Learning

This project implements an encoder-decoder neural network for translating CT images into MRI images. The model aims to enhance diagnostic accuracy and assist in treatment planning by generating MRI-like images from CT scans. The encoder-decoder architecture is used to learn a mapping between CT and MRI image pairs, with a focus on improving the quality of medical images for better analysis.

## Overview

The model leverages a deep learning approach to perform image translation from CT to MRI. The encoder network extracts features from the CT images, and the decoder network generates the corresponding MRI image. The training process minimizes the mean squared error (MSE) between the generated MRI image and the ground truth MRI image.

## Features

- **Encoder-Decoder Architecture**: Utilizes a deep neural network for image-to-image translation.
- **Mean Squared Error Loss**: The model uses MSE as the loss function for regression tasks, ensuring accurate pixel-wise predictions.
- **Improved Diagnostic Accuracy**: The translated MRI images are used to provide more detailed medical insights, enhancing diagnosis and treatment decisions.

## Setup

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ct-mri-image-translation.git
cd ct-mri-image-translation
