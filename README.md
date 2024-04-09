
---

# Alzheimer's Disease Detection Dataset

## Description

This dataset comprises MRI scans of individuals categorized into three classes based on their cognitive status: Mild Demented, Moderate Demented, and Non-Demented. The dataset is sourced from Kaggle and is used for Alzheimer's disease detection research. 

## Classes

1. **Mild Demented**: Individuals in this category show early signs of cognitive decline associated with Alzheimer's disease. Symptoms may include mild memory loss, difficulty solving problems, and communication issues. However, these symptoms do not significantly impair daily functioning.

2. **Moderate Demented**: Individuals at this stage exhibit more pronounced cognitive decline and functional impairment. Symptoms include worsening memory loss, confusion, disorientation, and difficulties with daily activities such as dressing and eating. Behavioral changes and increased dependency on others are common.

3. **Non-Demented**: Individuals in this category do not display significant cognitive impairment or symptoms associated with Alzheimer's disease. They may have normal cognitive function for their age and do not meet the criteria for dementia or Alzheimer's disease diagnosis.

## Folder Structure 

#### 1. Without GAN

This folder contains image data from Kaggle. It includes the following zipped folders:

- **test.zip**: This zip file contains the testing data for the Alzheimer's disease detection task.

- **train.zip**: This zip file contains the training data for the Alzheimer's disease detection task.

#### 2. With GAN

This folder contains both original images from Kaggle and data processed using Conditional Generative Adversarial Networks (cGANs) for augmentation. It includes the following zipped folders:

- **test1.zip**: This zip file contains the testing data augmented using cGANs.

- **train1.zip**: This zip file contains the training data augmented using cGANs.

## Usage

Researchers and developers can use this dataset for various purposes, including but not limited to:
- Alzheimer's disease detection research.
- Developing machine learning models for classification tasks.
- Studying the progression of Alzheimer's disease.

## Citation
[Dataset on Kaggle](https://www.kaggle.com/datasets/yasserhessein/dataset-alzheimer)

##DOI Link

[![DOI](https://zenodo.org/badge/784069127.svg)](https://zenodo.org/doi/10.5281/zenodo.10947536)
---
