# mango-leaf-disease-classification-intern-project.ipynb

Mango Leaf Disease Classification using CNN and Grad-CAM
Project Overview
This project implements a deep learning pipeline to classify diseases in mango leaves based on their images. It utilizes Convolutional Neural Networks (CNNs) for accurate disease classification and incorporates Grad-CAM visualization to interpret model predictions.

The entire workflow is designed to run smoothly on Google Colaboratory (Colab), leveraging free GPU acceleration for efficient training and evaluation.

Features
Data Preprocessing & Augmentation: Prepare and enhance the dataset for better model generalization.

CNN Model Training: Build and train convolutional neural networks tailored for image classification.

Grad-CAM Visualization: Generate heatmaps highlighting important regions in leaf images influencing the model’s decision.

Evaluation Metrics: Assess model performance with accuracy, loss, and other relevant metrics.

Easy to Use: Minimal setup required; fully runnable in Google Colab with step-by-step instructions.

Dataset
The dataset consists of images of mango leaves, categorized into folders named after different disease types.

Organize the dataset in the following structure for smooth integration:

Copy
Edit
dataset/
  ├── disease_1/
  ├── disease_2/
  ├── healthy/
  └── ...
You can upload the dataset directly to Colab or mount your Google Drive containing the dataset folder.

How to Run
Open the notebook file mango_leaf_disease_classification_intern_project.ipynb in Google Colab.

If your dataset or checkpoints are on Google Drive, mount the drive using the provided Colab commands.

Run the notebook cells sequentially from top to bottom.

Follow inline comments and explanations for clarity and better understanding.

Requirements
Python 3.x (already pre-installed in Colab)

Libraries:

TensorFlow / Keras

PyTorch (if applicable)

OpenCV

Matplotlib

Pandas

NumPy

Google Drive access (optional, for loading/saving datasets and models)

Additional Notes
The project includes Grad-CAM to visualize which parts of the mango leaf images most influence the model's classification decisions.

GPU acceleration on Colab will speed up training; ensure the runtime type is set to GPU (Runtime > Change runtime type > GPU).

