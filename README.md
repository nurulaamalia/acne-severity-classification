# Acne Severity Classification

This project aims to classify the severity of acne using a deep learning model. The model is built using the EfficientNet architecture and trained on a dataset of acne images.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Model Inference](#model-inference)
- [Links](#links)

## Installation

To install the necessary packages and modules, run:

```bash
pip install torch torchvision efficientnet_pytorch split-folders opencv-python-headless
```
## Dataset
The dataset can be downloaded from [kaggle](https://www.kaggle.com/datasets/gsaiman/acne-level).

To load the dataset in Google Colab, mount your Google Drive and set the dataset directory path.

## Data Preprocessing
We use split-folders to divide the dataset into training, validation, and testing sets. Preprocessing steps include histogram equalization, median filtering, and image enhancement.

## Model Training
The model is built using the EfficientNet architecture. The last layer is modified to fit the number of classes. The model is trained using the Adam optimizer and a learning rate scheduler.

## Evaluation
Evaluate the model on the validation and test sets to determine its performance. Key metrics include accuracy and loss.

## Links
[Hugging Face Model](https://huggingface.co/naamalia23/acne-severity-classification)
[Presentation](https://docs.google.com/presentation/d/1ZB8I-XdkwxMDuw1uQreAf86YuyBUND94/edit#slide=id.p1)
