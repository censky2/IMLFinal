# Brain Tumor MRI Analysis Project
## Overview
This project implements deep learning approaches for brain tumor detection and classification using MRI images. The system performs two main tasks:

1. Classification of brain tumors into different types (glioma, meningioma, pituitary, and no tumor)
2. Segmentation of tumor regions within MRI scans

## Dataset
Dataset source: Brain Tumor MRI Dataset:
https://www.kaggle.com/datasets/bilalakgz/brain-tumor-mri-dataset

## Code
### Classification.ipynb
Contains notebook for classification task.

### Segmentation.ipynb
Contains notebook for segmentation task.

### brain_tumor_generate_masks.ipynb
Notebook to generate mask image files. Run this before running Segmentation.ipynb.

### Process of running code
For classification task:
Step1: Download the dataset via link on notebook
Step2: Change the paths accordingly
Step3: Change the model as described in the comment
Step4: Run the Segemtaion.ipynb end to end

For Segmentation tasks:
Step1: Download the dataset via link on notebood
Step2: Change the paths accordingly
Step3: run the brain_tumor_generate_masks.ipynb to generate masks for images
Step4: Run the Segmentation.ipynb end to end

## Team Members
- Sky Cen
- Hanyu Zhu
- Yuhan Chen
