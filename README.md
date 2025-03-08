# Plant Disease Classification

## Overview
This project is a deep learning-based approach to classify plant diseases using the **PlantVillage Dataset**. The dataset consists of labeled images of leaves from various plant species, categorized by health condition and disease type.

## Dataset
- **Source**: [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- **License**: CC-BY-NC-SA-4.0
- **Content**: Images of leaves classified into healthy and diseased categories.

## Dependencies
To run this project, install the required dependencies:
```bash
pip install tensorflow numpy matplotlib kaggle
```

## Setup
1. **Kaggle API Setup**: Ensure you have a `kaggle.json` API key configured in `~/.kaggle/`.
2. **Download Dataset**:
   ```bash
   kaggle datasets download abdallahalidev/plantvillage-dataset
   ```
3. **Extract Dataset**:
   ```bash
   unzip plantvillage-dataset.zip -d data/
   ```

## Model Architecture
- Uses **TensorFlow** and **Keras** for deep learning.
- Implements **Convolutional Neural Networks (CNNs)** for image classification.
- Uses **ImageDataGenerator** for data augmentation.

## Training the Model
Run the notebook to train the model:
```bash
jupyter notebook Plant_disease.ipynb
```

## Results
- The trained model predicts plant disease
