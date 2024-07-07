# Brain Tumor Segmentation Using VGG16 U-Net Variants

This repository contains various deep learning models for brain tumor segmentation, leveraging the power of VGG16-based U-Net architectures. The project includes implementations of:

- VGG16 U-Net
- VGG16 Attention U-Net
- VGG16 Scaler Attention U-Net
- VGG16 MCA U-Net

## Table of Contents
- [Introduction](#introduction)
- [Models](#models)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to provide accurate brain tumor segmentation using advanced U-Net architectures. By leveraging VGG16 as the encoder backbone, these models achieve high performance in medical image segmentation tasks.

## Models
The repository contains implementations of the following models:
- `VGG16_U-Net`: Standard U-Net with VGG16 encoder.
- `VGG16_Attention_U-Net`: U-Net with attention mechanism added to the VGG16 encoder.
- `VGG16_Scaler_Attention_U-Net`: U-Net with scaler attention blocks.
- `VGG16_MCA_U-Net`: U-Net with multi-scale channel attention.

## Dataset
The models were trained and evaluated on a comprehensive dataset of brain MRI images with corresponding tumor masks.

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/ShubhamGajjar/Hybrid-Model-for-Brain-Tumor-Segmentation.git
cd BrainTumorSegmentation
pip install -r requirements.txt
