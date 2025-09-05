# Cancer Detection Using Histopathological Images

This project detects cancer from histopathological images using deep learning models built with TensorFlow and Keras. It demonstrates image preprocessing, model training (both from scratch and with transfer learning), evaluation, and model saving.

## Dataset
- Subset of 500 histopathological images (from Kaggle or similar source)
- Images are preprocessed and split into training and validation sets

## Features
- Image preprocessing and normalization
- Data augmentation using ImageDataGenerator
- Model training with a custom CNN
- Transfer learning using VGG16 pretrained on ImageNet
- Model evaluation and accuracy reporting
- Model persistence in Keras format

## Usage
1. Install dependencies:
	```bash
	pip install -r requirements.txt
	```

2. Run the Jupyter notebook:
	```bash
	jupyter notebook cancer_detection_histopathological_images.ipynb
	```

3. The notebook will:
	- Load and preprocess the dataset
	- Train and evaluate models
	- Save trained models as `model_manual.keras` and `model_transfer.keras`

## Files
- `cancer_detection_histopathological_images.ipynb`: Main notebook with code and explanations
- `dataset/`: Folder containing the images
- `model_manual.keras`: Saved custom CNN model
- `model_transfer.keras`: Saved transfer learning model

## Requirements
See `requirements.txt` for Python package dependencies.

## Author
Muhammad Huzaifa
