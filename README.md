# Convolutional Neural Network for Tumor Segmentation

### Overview
This repository contains a Convolutional Neural Network (CNN) project aimed at segmenting brain tumors from MRI scans using a 3D U-Net model.

### Features
- **3D U-Net Architecture:** Optimized for volumetric data to segment tumors effectively.
- **Custom Data Generator:** Facilitates loading and pre-processing MRI scan datasets.
- **Training and Evaluation:** Comprehensive notebooks to train and evaluate model performance on BraTS dataset.

### Files
- **Brats_tumor.ipynb:** Main notebook for tumor segmentation pipeline.
- **Custom_Data_gen.ipynb:** Custom data generator for handling volumetric MRI data.
- **Train_data.ipynb:** Dataset training notebook.
- **simple_3d_unet.ipynb:** Model implementation of a 3D U-Net for tumor segmentation.

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/shivam-bme/Convolutional-neural-network-for-tumor-segmentation.git
cd Convolutional-neural-network-for-tumor-segmentation
pip install -r requirements.txt
