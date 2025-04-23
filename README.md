# Image Classification for Garbage Classification
This project demonstrates how to build an image classification model for garbage classification using TensorFlow and Keras. The model is trained on a dataset of facial expressions and can be converted to different formats for deployment. The notebook includes steps for data preparation, model training, evaluation, and inference. Here's the link of dataset: [GarbageClassification](https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2)

## Overview
The project aims to classify facial expressions into 10 garbage categories:

Labels: Number of Images before preprocessing
- Metal: 1020
- Glass: 3061
- Biological: 997
- Paper: 1680
- Battery: 944
- Trash: 947
- Cardboard: 1825
- Shoes: 1977
- Clothes: 5327
- Plastic: 1984

The model is built using a pre-trained Xception as the base and fine-tuned for garbage classfication. It includes data augmentation, training, evaluation, and conversion to formats like TensorFlow Lite and TensorFlow.js for deployment.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/HerlyRyan/GarbageImageClassification
    cd GarbageImageClassification
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## How to Use
1. Open the notebook model_image_classification_submission.ipynb in your preferred IDE (e.g., PyCharm or Jupyter Notebook).
2. Follow the steps in the notebook:
    - Data preparation
    - Data augmentation
    - Model training
    - Evaluation and visualization
    - Model conversion
    - Inference
3. Run the cells sequentially to train the model and test its performance.

## Alternative
If you want to just learn of the code, check my google colab: [mycolab](https://colab.research.google.com/drive/1uFDnfiferIa_dILz0SQcDgJtddJzW041?usp=sharing)

## Another Model Links
The links show the another model that can't uploaded to this repo, because size larger than 100MB
[TFLite Model](https://drive.google.com/file/d/1zrKQ9l0X-22vjYrzVyd_94aM-PgEFVms/view?usp=sharing)
[Best Model Keras](https://drive.google.com/file/d/1bHlYoHMgnim9YM-MP0ES-k1hg2jagdoV/view?usp=sharing)
[HDF5 Model](https://drive.google.com/file/d/1BSpARbcPEHDRozuttM5o8AFDHLCZSs7D/view?usp=sharing)
[Saved Model](https://drive.google.com/drive/folders/142x1mqncyS2XZakDoDdG31EQX8-ITETb?usp=sharing)