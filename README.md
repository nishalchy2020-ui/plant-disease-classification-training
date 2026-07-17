# Plant Disease Classification using MobileNetV2 (PyTorch)

A deep learning project for plant leaf disease classification using **MobileNetV2**, **Transfer Learning**, and **Fine-Tuning** in PyTorch.

## Features

- MobileNetV2-based image classification
- Transfer learning from ImageNet
- Fine-tuning on the PlantDoc dataset
- Data augmentation for improved generalization
- Training, validation, and testing pipelines
- Accuracy and loss visualization
- Classification report and confusion matrix
- Model checkpoint saving
- Single image prediction

## Datasets

This project uses two publicly available datasets:

### 1. New Plant Diseases Dataset (PlantVillage)
- **Source:** Kaggle
- **Images:** ~87,000 RGB images
- **Classes:** 38 healthy and diseased plant classes
- **Link:** https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

### 2. PlantDoc Dataset
- **Source:** GitHub
- **Images:** Real-world plant leaf images
- **Purpose:** Fine-tuning and evaluating real-world performance
- **Link:** https://github.com/pratikkayal/PlantDoc-Dataset

## Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Pillow

## Evaluation

The project includes:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Training & Validation Loss Curves
- Training & Validation Accuracy Curves
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

## Repository Structure

```text
├── 01_plant_disease_detection.ipynb
├── 02_FineTune_PlantDoc.ipynb
├── models/
├── datasets/
└── README.md
```

## Future Improvements

- Support additional plant species
- Experiment with EfficientNet and Vision Transformers (ViT)
- Hyperparameter optimization
- Deploy as a Flask/FastAPI REST API
- Mobile and web application integration

## License

This project is intended for educational and research purposes.