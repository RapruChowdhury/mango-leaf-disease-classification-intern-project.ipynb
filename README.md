# Mango Leaf Disease Classification using CNN and Grad-CAM

## Project Overview
This project implements a deep learning pipeline to classify diseases in mango leaves from images using Convolutional Neural Networks (CNNs). It also incorporates **Grad-CAM** visualization to interpret and highlight important regions in the leaf images that influence the model's predictions.

The entire workflow is designed to run smoothly on **Google Colaboratory (Colab)**, leveraging free GPU acceleration for efficient training and evaluation.

---

## Features
- **Data Preprocessing & Augmentation:** Prepare and enhance the dataset to improve model generalization.
- **CNN Model Training:** Build and train CNN architectures tailored for image classification.
- **Grad-CAM Visualization:** Generate heatmaps to visualize key regions impacting the model’s decisions.
- **Evaluation Metrics:** Measure model performance using accuracy, loss, and other relevant metrics.
- **Easy to Use:** Minimal setup required with step-by-step instructions, fully runnable in Google Colab.

---

## Dataset
The dataset consists of images of mango leaves categorized into folders named after different disease types.

### Dataset Structure

dataset/
├── disease_1/
├── disease_2/
├── healthy/
└── ...
You can upload the dataset directly to Colab or mount your Google Drive containing the dataset folder for seamless integration.

###How to Run
-Open the notebook file mango_leaf_disease_classification_intern_project.ipynb in Google Colab.
-If your dataset or checkpoints are stored on Google Drive, mount the drive using the provided Colab commands.
-Run the notebook cells 


## Requirements

- Python 3.x (already pre-installed in Colab)

- Libraries:
  - TensorFlow / Keras
  - PyTorch (optional, if applicable)
  - OpenCV
  - Matplotlib
  - Pandas
  - NumPy

- Google Drive access (optional, for loading/saving datasets and models)
sequentially from top to bottom.
-Follow inline comments and explanations for clarity and better understanding.



