# U-Net for Road Segmentation in Mumbai using PyTorch

This project implements a U-Net deep learning architecture using PyTorch to perform semantic segmentation of road networks in Mumbai from satellite imagery.

## 📌 Project Overview

- **Objective**: Automatically identify and segment road infrastructure from satellite images.
- **Dataset**: Custom dataset of Mumbai roads annotated in GeoJSON format.
- **Model**: U-Net convolutional neural network.
- **Framework**: PyTorch.

## 🧠 Model Architecture

The U-Net model used here is composed of:

- Contracting path (encoder): to capture context
- Expanding path (decoder): to enable precise localization
- Skip connections between encoder and decoder layers

![U-Net Diagram](https://miro.medium.com/v2/resize:fit:828/format:webp/1*9p9cV08Lw3TOjKIPWJzDbg.png)



