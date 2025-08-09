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


## About Dataset

# Description
Type of data: 240x320 mango leaf images.
Data format: JPG.
Number of images: 4000 images. Of these, around 1800 are of distinct leaves, and the rest
are prepared by zooming and rotating where deemed necessary.
Diseases considered: Seven diseases, namely Anthracnose, Bacterial Canker, Cutting Weevil,
Die Back, Gall Midge, Powdery Mildew, and Sooty Mould.
Number of classes: Eight (including the healthy category).
Distribution of instances: Each of the eight categories contains 500 images.
How data are acquired: Captured from mango trees through the mobile phone camera.
Data source locations: Four mango orchards of Bangladesh, namely Sher-e-Bangla Agricultural
University orchard, Jahangir Nagar University orchard, Udaypur village
mango orchard, and Itakhola village mango orchard.

Where applicable: Suitable for distinguishing healthy and diseases leaves (two-class
prediction) as well as for differentiating among various diseases (multi-
class prediction).

### Please cite the following if you use this dataset:

Ali, Sawkat; Ibrahim, Muhammad ; Ahmed, Sarder Iftekhar ; Nadim, Md. ; Mizanur, Mizanur Rahman; Shejunti, Maria Mehjabin ; Jabid, Taskeed (2022), “MangoLeafBD Dataset”, Mendeley Data, V1, doi: 10.17632/hxsnvwty3r.1

### How to Run
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



