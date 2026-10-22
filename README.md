# CycleGAN Image to Image Translation

1.

## Overview
What if you get a self-portrait from a very famous Dutch Post-Impressionist painter Vincent van Gogh? Sounds impossible, right? But in recent years, researchers from Microsoft have developed the Cycle GAN model specifically for unpaired image-to-image translation. There are several use cases of the Cycle GAN model, from Photograph Enhancement to Season or Style Transfer. With the help of this model, you can translate any image to any other domain irrespective of the pairing between two images. This project will walk you through all the components of Cycle GAN with developing the Cycle GAN model from scratch in PyTorch.

## Data
The dataset contains horse images in domain A, and zebra images in domain B, which is split into train and test sets.

_Data is not included in this repository._

## Approach
1. Introduction to Cycle GAN
2. Introduction to ResNet
3. Loss function in Cycle GAN
4. Building Model on PyTorch
5. Model training

Prerequisites
1. PyTorch Project to Build a GAN Model on MNIST Dataset
2. Learn How to Build PyTorch Neural Networks from Scratch

Modular code overview

Once you unzip the CycleGAN_code.zip file, you can find the following folders within it.
1. data
2. images
3. saved_model
4. cyclegan.py
5. datasets.py
6. models.py
7. utils.py
8. requirements.txt
1. The data folder contains horse2zebra dataset. It is split into train and test sets with domain A as Horse and domain B as Zebra.
2. The images folder contains translated images from the domain A to B.
3. The models.py, dataset.py, and utils.py files contain the code for model training which are called inside the cyclegan.py file.
4. The requirements.txt file has all the required libraries with respective versions. Kindly install the file by using the command pip install -r requirements.txt

## Tech stack
➔ Language: Python ➔ Libraries: torch, torchvision, numpy, pillow

## How to run
```bash
pip install -r CycleGAN_Code/requirements.txt
```

## Project structure
```
.gitignore
CycleGAN_Code/
  cyclegan.py
  datasets.py
  models.py
  requirements.txt
  utils.py
README.md
```

## Credits
Based on a ProjectPro guided project.
